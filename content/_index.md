+++
title = "About"
description = "About me."
weight = 0
template = "page.html"
sort_by = "weight"
+++
I am a cryptologist at Thales.

I completed my PhD in the *équipe-projet* [COSMIQ (previously SECRET)](https://www.rocq.inria.fr/cosmiq) at Inria Paris under the supervision of [Nicolas Sendrier](https://www.rocq.inria.fr/secret/Nicolas.Sendrier).

# Research interests

I am interested in Moderate Density Parity Check (MDPC) {{ doi(id="10.1109/ISIT.2013.6620590") }} {{ eprint(id="2012/409") }} codes, more specifically I am interested in their decoders.
This type of codes is defined similarly to Low Density Parity Check (LDPC) codes, the main difference is the number of ones in the rows of the parity check matrix: a small constant for LDPC but in \\(\mathcal{O}(\sqrt{n})\\) for MDPC (with \\(n\\) the length of the code).
This difference in density allows for a McEliece-like public key cryptosystem whose secret key attacks and message attacks reduce to hard problems on codes.

The [NIST PQC](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography) candidate [BIKE](https://bikesuite.org) is based on the quasi-cyclic MDPC codes.

# Contact

[Email](mailto:valentin.vasseur@gmail.com)
