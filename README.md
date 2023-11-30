# Stuff with Signatures

Digital signatures allow us to verify that a piece of data has been unmodified and was produced by a certain entity. They are especially useful in the context of zero-knowledge proofs, where they enable a party with access to the signature and its underlying data to prove properties about the data without revealing the data itself. 

To aid the development of zero-knowledge applications and the adoption of digital signatures as a whole, here is a list of types of data in the world that come with digital signatures, along with projects that generate zero-knowledge proofs about them.

**Want to contribute?** Submit a pull request!

## The List
- Email ([DKIM signatures](https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail))
	- [PROJECT] [ZK Email](https://github.com/zkemail)