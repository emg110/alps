# ALPS

Algorand Proof Service is a **Entity Proof Service**  based on Algorand blockchain. A comprehensive and industry standard proof system service based on Algorand layer one features: ASA, ASC and AAT. The idea comes from POAP but extends it dramatically. This should not be mistaken with internal pure proof of stake model of Algorand because this is a completely outbound service using blockchain features of Algorand and cares not about how the chain deals with proof of stake or defines it. For example, proof of stake with ALPS uses TEAL feature of reading remainder account balance on token and checks it to be above configured treshhold in ALPS rules.

Proof systems are a very important usecase of blockchain services and , for example unlike NFTs, they do not have monetization and commerce intentions in the first place but come in more of an added value service in flavor.

#### POAP was an starter proof on concept for such implementations and lacks many features when it comes to industry and production requirements, especially in mission-critical systems with specific requirements and constraints which demands more complex and hybrid proof systems beyond just issuing and holding a named token with some smart contracts to seal the proof!

Includes multi factor proof system micro dApps and services:

- Proof of Attendance (similar to POAP but much more advanced and industry ready.).
- Proof of Presence (Contigous presence).
- Proof of Stake (Minimum holding of token with event and window modes)
- Proof of Provenance.
- Proof of Location (location point, track and boundary modes).
- Proof of Time (Event and window modes).
- Proof of Identity (aka authentication)
- Proof of Access (aka access control)
- Proof of Permission (aka authorization)
- Proof of Content (Tamper-proof content integrity)
