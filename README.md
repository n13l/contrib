### OpenVPN: Added support for TLS Keying Material Exporters
Keying Material Exporter allows additional keying material to be derived from an existing TLS channel, and this exported keying material can then be used for a variety of purposes. Channel bindings provide a straightforward and well-defined mechanism to authenticate other layers. Upper layer authentication based on derived keying material does not require any additional session state, session identifier, or session key transfer between the endpoints, significantly reducing security risks. It binds a specific user to the secured channel and reduces the need for weak application layer authentication, as well as reducing any costs related to additional application layer session management.

[https://github.com/OpenVPN/openvpn/blob/master/doc/keying-material-exporter.txt
](https://github.com/OpenVPN/openvpn/blob/master/doc/keying-material-exporter.txt)

### OpenAAA: TLS Side-Channel Authentication Based on Decentralized Trust
TLS authentication based on decentralized trust and straightforward
bindings of AAA information to application layer using well-defined mechanism.

[https://github.com/n13l/openaaa/blob/master/doc/tls-sca
](https://github.com/n13l/openaaa/blob/master/doc/tls-sca)
