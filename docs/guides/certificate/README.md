---
menu:
  product_voyager_5.0.0-rc.8:
    identifier: certificate-readme
    name: Overview
    parent: certificate
    weight: 10
product_name: voyager
menu_name: product_voyager_5.0.0-rc.8
section_menu_id: guides
url: /products/voyager/5.0.0-rc.8/guides/certificate/
aliases:
  - /products/voyager/5.0.0-rc.8/guides/certificate/README/
---

# Certificate

Voyager comes with a built-in certificate manager that can issue free TLS/SSL certificates from Let's Encrypt. Voyager uses a Custom Resource Definition called `Certificate` to declaratively manage and issue certificates from Let's Encrypt.

## Features
- Provision free TLS certificates from Let's Encrypt.
- Manage certificates declaratively using a Kubernetes Custom Resource Definition (CRD).
- Domain validation using ACME http-01 and dns-01 challenges.
- Support for many popular [DNS providers](/docs/guides/certificate/providers.md).
- Auto Renew certificates.
- Use issued certificates with Ingress to secure communications.

## Next Steps
- [Issue Let's Encrypt certificate using HTTP-01 challenge](/docs/guides/certificate/http.md)
- DNS-01 chanllege providers
  - [Issue Let's Encrypt certificate using AWS Route53](/docs/guides/certificate/route53.md)
  - [Issue Let's Encrypt certificate using Google Cloud DNS](/docs/guides/certificate/google-cloud.md)
  - [Supported DNS Challenge Providers](/docs/guides/certificate/providers.md)
- [Deleting Certificate](/docs/guides/certificate/delete.md)
- [Frequently Asked Questions](/docs/guides/certificate/faq.md)