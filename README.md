# The MarsaTag software

Scientific fields: Natural Language Processing, Automatic tagging of the syntax of written and
spoken French.

MarsaTag is a system aiming at segmenting, tagging and chunking French input. The originality of the
tool, on top of its efficiency, is its ability to process written texts as well as speech transcriptions. The
tagger executes the three following operations. First, a rule-based tokenizer splits the raw textual input
in a sequence of tokens. In a second step, thanks to a broad-coverage morphosyntactic lexicon, each
token form is associated to a tag distribution. The last step consists in disambiguating the tagging by
selecting the POS tag sequence with the highest probability. The probability of a sequence of tags is
computed thanks to a stochastic model using the Hidden Markov Model machinery. The states or
patterns of our model are extracted from the GraceLPL resource (700,000 tokens with morphosyntactic
annotation). The performance of the tagger reaches an F-measure score of 0.974 for written material.
The tagger has been adapted for the treatment of spontaneous speech transcriptions (see the chapter
« Annotations » of the LPL book). The system has been trained with a large spoken French corpus (CID,
see Bertrand et al., 2008). Phenomena proper to speech (filled paused, disfluencies, truncation, etc.)
were identified and included in a model specific to speech transcription inputs. The tagger performance
of 0.948 (F-measure) has been evaluated on the manual corrected tags of the CID corpus. MarsaTag is
freely distributed with a software interface allowing the choice of various input and output formats
(url : https://www.ortolang.fr/market/tools/sldr000841).

On this GitHub page, you can download the .exe or .jar installers that allow to install the java version of the MarsaTag software (version 0.8.5) on your computer.
The pdf documentation of MarsaTag is in the folder where you installed MarsaTag, i.e. MarsaTag\docs\MarsaTag-UI.pdf

The encoding of the morphosyntactic tags is given in the chapter Annexes:Morphosyntactic tags of this document.
This encoding is also summarized in the xml document LPL_MSE.xml that you can download here.
For example, the tag "Pp3msn-" stands for Pronoun (P), personal (p), third person (3), masculine (m), singular (s), nominative (n).

REFERENCES

[Rauzy et al., 2022] Stéphane Rauzy, Grégoire de Montcheuil, Philippe Blache. The MarsaTag software. Travaux Interdisciplinaires sur la Parole et le Langage, 2022, 38, ⟨10.4000/tipa.5735⟩. [⟨hal-03962331⟩](https://hal.science/hal-03962331v1)

[Rauzy et al., 2014] Stéphane Rauzy, Grégoire Montcheuil, Philippe Blache. MarsaTag, a tagger for
French written texts and speech transcriptions. Second Asian Pacific Corpus linguistics Conference, Mar
2014, Hong Kong, China. pp.220-220. [⟨hal-01500736⟩](https://hal.science/hal-01500736v1)

[Rauzy&Blache, 2009] Stéphane Rauzy, Philippe Blache. Un point sur les outils du LPL pour l'analyse
syntaxique du français. Journée ATALA "Quels analyseurs syntaxiques pour le français ?", Oct 2009,
Paris, France. pp.1-6. [⟨hal-00433879⟩](https://hal.science/hal-00433879v1)

# Le logiciel MarsaTag

Domaine d’activité : Traitement Automatique des Langues, étiquetage syntaxique automatique du français écrit ou parlé

MarsaTag est un système qui permet de segmenter, d’étiqueter et d’analyser en chunks des
productions du français. L’originalité de l’outil réside dans sa capacité à traiter autant du français écrit
que de des transcriptions du français parlé. L’étiqueteur effectue les trois opérations suivantes. Un
segmenteur à base de règles est d’abord appliqué au texte en entrée afin de le séparer en une séquence
de tokens. Dans un deuxième temps, grâce à un lexique morphosyntaxique de large couverture, le
système associe à chaque forme orthographique identifiant le token sa distribution de catégories
morphosyntaxiques correspondantes. La dernière étape consiste à désambiguïser l’étiquetage en
proposant en sortie la séquence d’étiquettes possédant la probabilité maximale. La probabilité d’une
séquence est calculée à partir d’un modèle stochastique dans le cadre du formalisme de Chaines de
Markov Cachées (HMM). Les états ou « patrons » du modèle ont été extrait de la ressource GraceLPL
(700 000 tokens avec un étiquetage morphosyntaxique). La performance de l’étiqueteur atteint un
score de F-mesure de 0.974. L’étiqueteur a été adapté pour traiter les transcriptions du français parlé
(voir le chapitre « Annotations » du livre du LPL). Le système a été entraîné sur le CID (Bertrand et al.,
2008), un grand corpus français de parole spontanée en interaction. Les phénomènes propres à l’oral
(pause remplies, disfluences, troncations, …) ont été identifiés et inclus dans le modèle spécifique au
traitement des transcriptions en entrée. La performance de l’étiqueteur pour l’oral (0.948 de F-mesure)
a été évalué sur la correction manuelle des étiquettes morphosyntaxiques du CID. Le logiciel MarsaTag
est distribué librement avec une interface graphique qui permet un vaste choix de format d’entrée
sortie (url : https://www.ortolang.fr/market/tools/sldr000841).

Sur cette page GitHub, vous pouvez télécharger les installeurs (.exe ou .jar) qui vous permettent d'installer sur votre ordinateur le logiciel MarsaTag (version 0.8.5) codé en java. 
La documentation pdf de MarsaTag est dans le dossier dans lequel vous avez installé MarsaTag, i.e. MarsaTag\docs\MarsaTag-UI.pdf

L'encodage des étiquettes morphosyntaxiques est donné dans le chapitre Annexes:Morphosyntactic tags de la documentation.
Cet encodage est aussi résumé dans le document LPL_MSE.xml que vous pouvez charger ici.
Par exemple, l'étiquette "Pp3msn-" encode l'information Pronoun (P), personal (p), third person (3), masculine (m), singular (s), nominative (n).

REFERENCES

[Rauzy et al., 2022] Stéphane Rauzy, Grégoire de Montcheuil, Philippe Blache. The MarsaTag software. Travaux Interdisciplinaires sur la Parole et le Langage, 2022, 38, ⟨10.4000/tipa.5735⟩. [⟨hal-03962331⟩](https://hal.science/hal-03962331v1)

[Rauzy et al., 2014] Stéphane Rauzy, Grégoire Montcheuil, Philippe Blache. MarsaTag, a tagger for
French written texts and speech transcriptions. Second Asian Pacific Corpus linguistics Conference, Mar
2014, Hong Kong, China. pp.220-220. [⟨hal-01500736⟩](https://hal.science/hal-01500736v1)

[Rauzy&Blache, 2009] Stéphane Rauzy, Philippe Blache. Un point sur les outils du LPL pour l'analyse
syntaxique du français. Journée ATALA "Quels analyseurs syntaxiques pour le français ?", Oct 2009,
Paris, France. pp.1-6. [⟨hal-00433879⟩](https://hal.science/hal-00433879v1)

