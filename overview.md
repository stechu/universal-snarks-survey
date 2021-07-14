## Universal SNARKs Overview

### State of Art Systems

Currently, three concrete constructions are considered state-of-art:

* Marlin: https://eprint.iacr.org/2019/1047.pdf
* Plonk: https://eprint.iacr.org/2019/953.pdf
* Halo2: https://electriccoin.co/blog/explaining-halo-2/

### Building Blocks and Techniques

1. Polynomial commitment
   * [KZG10](https://www.iacr.org/archive/asiacrypt2010/6477178/6477178.pdf)
   * [Sonic's KZG Variant (section 6.2 of Sonic)](https://eprint.iacr.org/2019/099.pdf)
   * [Batching KZG (section 3 of Plonk paper, based on KZG and Sonics' PC)](https://eprint.iacr.org/2019/953.pdf)
   * [Marlin's PC (section 6 of Marlin paper, need more work to compare)](https://eprint.iacr.org/2019/1047.pdf)

2. Recursive SNARKs and PCD
   * [Halo Infinite: Recursive zk-SNARKs from any Additive Polynomial Commitment Scheme](https://eprint.iacr.org/2020/1536)
   * [Proof-Carrying Data from Accumulation Schemes](https://eprint.iacr.org/2020/499)
   * [Proof-Carrying Data without Succinct Arguments](https://eprint.iacr.org/2020/1618)

3. Updatable CRS (or so called SRS)
   * [Updatable and Universal Common Reference Strings with Applications to zk-SNARKs](https://eprint.iacr.org/2018/280.pdf)

4. Proving Techniques (for security proofs)
   * [Algebraic Group Model](https://eprint.iacr.org/2017/620.pdf)
