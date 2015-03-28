# Glossary

|                 |        |
|-----------------|--------|
| [channel][]              | a virtual socket that allows two _endpoints_ to exchange data reliably (like TCP or unreliably UDP)
| [cloaking][]             | method used to hides telehash traffic on the wire by randomizing all data sent
| [CS][]                   | (Cipher Set) a collection of crypto algorithms with a given _CSID_
| [CSID][]                 | (Cipher Set ID) predefined hex number identifying a _CS_
| [CSK][]                  | (Cipher Set Key) the public key bytes for a given _CSID_
| [endpoint][]             | a participant in the telehash network identified by a single _hashname_
| [E3X][]                  | End-to-End Encrypted eXchange is a flexible encrypted exchange protocol
| [exchange][]             | the current encrypted session state between two endpoints
| [handshake][]            | _message_ type used to establish an encrypted _session_ for _channels_
| [hashname][]             | an identifier for a participant of telehash, it is calculated from all public keys of the participants _cipher set (CS)_
| [LOB][]                  | Lenght-Oobject-Binary encoding format that allows combining JSON and binary data
| [link][]                 | connection between two _endpoints_ either directly or via a _router_
| [mesh][]                 | a number of _links_ with active encrypted _sessions_ over any _transport_, participants in the mesh are called _endpoints_
| [message][]              | an asynchronous encrypted packet between two endpoints
| [packet][]               | an encapsulation format for JSON and binary data using _length object binary (LOB)_ encoding
| [router][]               | an endpoint that will facilitate connection setup between two other endpoints
| [transport][]            | underlying layer responsible for _packet_ transfer
| [URI][]                  | using a [Uniform rescource identifier](http://en.wikipedia.org/wiki/Uniform_resource_identifier) to enable endpoints to share enough information (_hashname_, _transport_) for out-of-band connection setup and references

[channel]: channels/
[cloaking]: cloaking.md
[CS]: e3x/cs/
[CSID]: e3x/cs/
[CSK]: e3x/cs/
[endpoint]: link.md
[E3X]: e3x/
[exchange]: e3x/
[handshake]: e3x/handshake.md
[hashname]: hashname.md
[LOB]: lob.md
[link]: link.md
[mesh]: mesh.md
[message]: e3x/messages.md
[packet]: lob.md
[router]: link.md
[transport]: transports/
[URI]: uri.md