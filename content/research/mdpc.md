+++
title = "MDPC"
description = "More about MDPC."
weight = 0
template = "page.html"
+++
LDPC decoders can decode MDPC codes with some small adjustments but the higher density of the parity check matrix negatively impacts the performance of the algorithm.
As a consequence, MDPC decoders will fail with a small but nonzero probability.
Guo, Johansson and Stankovski showed {{ doi(id="10.1007/978-3-662-53887-6_29") }} {{ eprint(id="2016/858") }} that by collecting many plaintexts together with the information that the associated ciphertext is successfully decoded or not the secret key can be recovered.
As this method requires many plaintexts whose ciphertext fails to decode, this is not an issue if the cryptosystem uses ephemeral key.
On the other hand, static key encryption requires a really small Decoding Failure Rate (DFR) in order to have IND-CCA security.

I thus focus on:
- improving the MDPC decoder and reduce the DFR to a quantity as small as \\(2^{-128}\\) for example;
- proving the DFR of the decoder.
