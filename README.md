### OpenVPN: Added support for TLS Keying Material Exporters
Keying Material Exporter allows additional keying material to be derived from an existing TLS channel. This exported keying material can then be used for a variety of purposes. Keying material used for TLS strong mutual side-channel authentication and channel bindings provides a straightforward and well-defined mechanism to authenticate upper layers. Upper layer authentication based on an existing secured channel does not require any session state or session identifier transfer over the application layer, significantly reducing security risks and providing identifiers and session keys for both endpoints.

[https://github.com/OpenVPN/openvpn/blob/master/doc/keying-material-exporter.txt
](https://github.com/OpenVPN/openvpn/blob/master/doc/keying-material-exporter.txt)

### OpenAAA: TLS Side-Channel Authentication Based on Decentralized Trust
TLS authentication based on decentralized trust and straightforward
bindings of AAA information to application layer using well-defined mechanism.

[https://github.com/n13l/openaaa/blob/master/doc/tls-sca
](https://github.com/n13l/openaaa/blob/master/doc/tls-sca)
