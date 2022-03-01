+++
title = "PhD Defence"
description = "Information about my PhD Defence."
weight = 5
url = "phd_defence"
template = "page.html"
+++

## Cryptographie post-quantique : étude du décodage des codes QC-MDPC
## Post-quantum cryptography: study on the decoding of QC-MDPC codes
### 29/03/2021 - 14h (UTC+02:00)

{{ static_res(path="/papers/2021-03-29-thesis-Vasseur.pdf", text="Dissertation") }} and
{{ static_res(path="/papers/2021-03-29-slides-Vasseur.pdf", text="slides") }} are in English.

The presentation will be given in French.

### Résumé

La cryptographie post-quantique vise à sécuriser les échanges contre un adversaire disposant d'un ordinateur quantique.
L'une des approches envisagées pour permettre un chiffrement à clé publique post-quantique repose sur des problèmes difficiles en théorie des codes.
Le mécanisme d'encapsulation de clé BIKE, soumis au processus de standardisation post-quantiques du NIST, utilise des codes QC-MDPC dont la quasi-cyclicité permet une représentation compacte de la clé.
Cependant, leurs algorithmes de décodage ont une probabilité d'échec (DFR) non nulle, ce qui peut poser un problème de sécurité comme l'ont démontré Guo, Johansson et Stankovski.
Ce travail se concentre donc sur l'implémentation et la sécurité de BIKE du point de vue du décodeur.
Premièrement, nous concevons de nouveaux algorithmes qui réduisent drastiquement le DFR.
Ensuite, nous développons des modèles probabilistes pour prédire le DFR dans des zones hors de portée des simulations.
Enfin, nous en déduisons une méthode d'extrapolation du DFR et nous évaluons son adéquation avec des caractéristiques structurelles du code qui peuvent affecter le processus de décodage.

### Abstract

Post-quantum cryptography aims at securing exchanges against an adversary with a quantum computer.
One approach considered to achieve post-quantum public key encryption relies on hard problems in coding theory.
The key encapsulation mechanism BIKE, submitted to the NIST post-quantum standardization process, uses QC-MDPC codes whose quasi-cyclicity allows for a compact key representation.
However, their decoding algorithms have a non-zero probability of failure (DFR) and this can be a security concern as demonstrated by Guo, Johansson and Stankovski.
This work therefore focuses on the implementation and security of BIKE from the decoder's perspective.
This is done first by designing new algorithms that drastically reduce the DFR.
Second, we develop probabilistic models to predict the DFR in areas out of reach by simulations.
Finally, we derive a method for extrapolating the DFR and we evaluate its adequacy with structural characteristics of the code that can affect the decoding process.

### Jury

- {{ jurymember(firstname="Nicolas",     lastname="Sendrier", institution="Inria",                 function="Directeur") }}
- {{ jurymember(firstname="Jérôme",      lastname="Lacan",    institution="ISAE-Supaero",          function="Rapporteur") }}
- {{ jurymember(firstname="Pierre",      lastname="Loidreau", institution="Université de Rennes",  function="Rapporteur") }}
- {{ jurymember(firstname="Alain",       lastname="Couvreur", institution="Inria",                 function="Examinateur") }}
- {{ jurymember(firstname="Caroline",    lastname="Fontaine", institution="ENS Paris-Saclay",      function="Examinatrice") }}
- {{ jurymember(firstname="Philippe",    lastname="Gaborit",  institution="Université de Limoges", function="Examinateur") }}
- {{ jurymember(firstname="Sophie",      lastname="Laplante", institution="Université de Paris",   function="Examinatrice") }}
- {{ jurymember(firstname="Jean-Pierre", lastname="Tillich",  institution="Inria",                 function="Examinateur") }}

