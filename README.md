# Stuff with Signatures

Digital signatures allow us to verify that a piece of data has been unmodified and was produced by a certain entity. They are especially useful in the context of zero-knowledge proofs, where they enable a party with access to the signature and its underlying data to prove properties about the data without revealing the data itself. 

To aid the development of zero-knowledge applications and the adoption of digital signatures as a whole, here is a list of types of data in the world that come with digital signatures, along with projects that generate zero-knowledge proofs about them.

**Want to contribute?** Submit a pull request!

## The List
- Email ([DKIM signatures](https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail))
	- [PROJECT] [ZK Email](https://github.com/zkemail)
	- [PROJECT] [ZKP2P](https://github.com/zkp2p/zk-p2p)
- Passports (150+ countries have [biometric/e-passports](https://en.wikipedia.org/wiki/Biometric_passport))
	- [PROJECT] [Proof of Passport](https://github.com/zk-passport/proof-of-passport)
- EU [Residence Cards](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32017R1954) for foreign nationals
- [eIDAS](https://digital-strategy.ec.europa.eu/en/policies/eidas-regulation) (future electronic id cards for EU citizens)
- Credit Card Transactions ([EMV](https://en.wikipedia.org/wiki/EMV) cryptograms)
	- [PROJECT] [GOAT RAMP](https://ethglobal.com/showcase/goat-ramp-futsg)
- HTTPS/TLS (signatures are only used during the key-exchange handshake, to prove authenticity of sessions a workaround is needed)
	- [PROJECT] [TLS Notary](https://tlsnotary.org/) (Performs an MPC with a 3rd party notary)
	- [PROJECT] [Reclaim Protocol](https://www.reclaimprotocol.org/) (A 3rd party provides an attesting signature)
- Git commits
- [Sign Protocol](https://docs.ethsign.xyz/sign-protocol), an omni-chain attestation protocol, enabling users to attest and verify any information on-chain freely
- Ethereum Attestation Service ([EAS](https://attest.sh/)), including [Coinbase onchain verification](https://help.coinbase.com/en/coinbase/getting-started/verify-my-account/onchain-verification) and [Gitcoin Passport](https://passport.gitcoin.co/)
- [Proof of Humanity](https://proofofhumanity.id/)
- PDFs (some PDFs e.g. [Docusign](https://www.docusign.com/how-it-works/electronic-signature/digital-signature/digital-signature-faq) are digitally signed by certificate authorities)
	- [PROJECT] [zkCert](https://github.com/zkCert/halo2-zkcert)

### National ID Cards
- India's Aadhaar
	- [PROJECT] [Anon aadhaar](https://github.com/privacy-scaling-explorations/anon-aadhaar)
- Japan's My Number Cards
	- [PROJECT] [Myna Wallet](https://github.com/MynaWallet/monorepo)
- Taiwan DID
	- [PROJECT] [tw-did](https://github.com/tw-did/tw-did/)

### Onchain data
- Ethereum transactions and state
	- [PROJECT] [Axiom](https://github.com/axiom-crypto/axiom-eth)
- Poaps
- Semaphore identities
