---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/201296?"
user: zakird
date: 2020-12-08
repo_name: zmap/zcrypto
html_url: https://github.com/zmap/zcrypto/commit/946fec672f0ae223f5e1d01b698d6cb8852722f6
repo_url: https://github.com/zmap/zcrypto
---

<a href='https://github.com/zakird' target='_blank'>zakird</a> pushed to <a href='https://github.com/zmap/zcrypto' target='_blank'>zmap/zcrypto</a>

<small>tls: Advertise rsa_pkcs1_sha{256,384,512} support by default (#222)

* tls: Advertise rsa_pkcs1_sha{256,384,512} support by default

When populating for the signature_algorithms extension,
defaultSKXSignatureAlgorithms is used by default for TLS1.2. We
have support for rsa_pkcs1_sha{256,384,512}, and some servers
require these to at least be advertised.  Add them in to the
default list.

* comment out handshake transcript tests

Co-authored-by: Zakir Durumeric <zakird@gmail.com></small>

<a href='https://github.com/zmap/zcrypto/commit/946fec672f0ae223f5e1d01b698d6cb8852722f6' target='_blank'>View Commit</a>