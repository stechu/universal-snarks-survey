Snark Friendly Curves
=====================

There are two promising solutions with good performance and security trade-off (BN is not considered for the security concern brought by NFV attacks).

1. BLS381 + Bandersnatch
This uses Bandersnatch replaces the commonly used Jubjub, with faster scalar multiplication speed. 

References:
- [ETH research post](https://ethresear.ch/t/introducing-bandersnatch-a-fast-elliptic-curve-built-over-the-bls12-381-scalar-field/9957)
- [Curve math construction](https://github.com/asanso/Bandersnatch)
- [Curve implementation (only the Bandersnatch part)](https://github.com/arkworks-rs/curves/tree/master/ed_on_bls12_381_bandersnatch)


2. Pasta: Palla + Vesta
This curve combination is ZCash uses for its next generation proof system - Halo2. 

References:
- [ZCash Blog post](https://electriccoin.co/blog/the-pasta-curves-for-halo-2-and-beyond/)
- [Curve math Construction](https://github.com/zcash/pasta)
- [Curve implementation 1 - ZCash](https://github.com/zcash/pasta_curves)
- [Curve implementation 2 - Pallas part](https://github.com/arkworks-rs/curves/tree/master/pallas)
- [Curve implementation 2 - Vesta part](https://github.com/arkworks-rs/curves/tree/master/vesta)

(TODOs: comparing 1 and 2 from different aspect)