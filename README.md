# Personal Efforts in Open Source Security

## OPENVPN
### Added support for [RFC5705] TLS Keying Material Exporters
Keying Material Exporter [RFC-5705] allow additional keying material to be
derived from existing TLS channel. This exported keying material can then be
used for a variety of purposes. TLS allows client and server to establish
keying material for use in the upper layers between the TLS end-points and
channel bindings is straightforward and well-defined mechanism how to
authenticate other layers.

[https://github.com/OpenVPN/openvpn/blob/master/doc/keying-material-exporter.txt
](https://github.com/OpenVPN/openvpn/blob/master/doc/keying-material-exporter.txt)

## OPENAAA
## Mutual TLS Side-Channel Authentication Based on Decentralized Trust
TLS authentication based on decentralized trust and straightforward
bindings of AAA information to application layer using well-defined mechanism.

[https://github.com/n13l/openaaa/blob/master/doc/tls-sca
](https://github.com/n13l/openaaa/blob/master/doc/tls-sca)


