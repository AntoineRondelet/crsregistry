# CRS Registry

This repository consolidates resources about various instances of MPC protocols for CRS/SRS generation.

## BN254

- Ignition:
    - Setup output: [To be added]
    - Proof system: Plonk
    - Source:
        - https://github.com/AztecProtocol/Setup
        - https://github.com/AztecProtocol/ignition-verification

- Perpetual Powers of Tau:
    - Setup output: https://github.com/weijiekoh/perpetualpowersoftau
    - Proof system: Groth16
    - Source:
        - https://github.com/kobigurk/phase2-bn254
        - https://github.com/iden3/snarkjs

- Zcash Sprout:
    - Setup output: https://z.cash/technology/paramgen/#sprout-mpc
    - Proof system: [PGHR13](https://eprint.iacr.org/2013/279)
    - Source:
        - https://github.com/zcash/mpc
    - Paper: https://www.ieee-security.org/TC/SP2015/papers-archived/6949a287.pdf

- Zcash Powers of Tau:
    - Setup output:
        - https://www.zfnd.org/blog/conclusion-of-powers-of-tau/
        - Attestations: https://github.com/ZcashFoundation/powersoftau-attestations/
    - Proof system: Groth16
    - Source: 
        - https://github.com/ebfull/powersoftau/
    - Paper: https://eprint.iacr.org/2017/1050

- Zcash Sapling:
    - Setup output: https://electriccoin.co/blog/completion-of-the-sapling-mpc/
    - Proof system: Groth16
    - Source:
        - https://github.com/zcash-hackworks/sapling-mpc
    - Paper: https://eprint.iacr.org/2017/1050

- Tornado Cash:
    - Setup output: https://ceremony.tornado.cash/
    - Proof system: Groth16
    - Source:
        - https://github.com/tornadocash/phase2-bn254
        - https://github.com/tornadocash/trusted-setup-server
    - Misc:
        - https://tornado-cash.medium.com/tornado-cash-trusted-setup-ceremony-b846e1e00be1
        - https://tornado-cash.medium.com/the-biggest-trusted-setup-ceremony-in-the-world-3c6ab9c8fffa#43d9


## BLS12-381

- Filecoin:
    - Setup output:
        - https://trusted-setup.filecoin.io/
        - https://github.com/arielgabizon/perpetualpowersoftau
        - https://github.com/filecoin-project/phase2-attestations
    - Proof system: Groth16
    - Source:
        - https://github.com/filecoin-project/powersoftau/
        - https://github.com/filecoin-project/filecoin-phase2
    - Misc: https://filecoin.io/blog/posts/trusted-setup-complete/


## BW6

- Plumo:
    - Setup output:
        - https://celo.org/plumo
        - https://github.com/celo-org/plumo-ceremony-attestations
    - Misc: https://medium.com/celoorg/the-plumo-ceremony-ac7649e9c8d8

----------------------------

## Other references

- https://z.cash/technology/paramgen/
