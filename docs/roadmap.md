# Kong Ingress controller Roadmap

This document contains open questions and features for the ingress controller.
The order is not related to their priority.

- Use tags in resources created in Kong.
- Do not replace object manually created in the Kong admin API.
- Allow custom upstream configurations (Kong Service).
- Leader election to allow multiple instances of the ingress controller.
- Status update of Ingress.
- Add support to update Kong certificates
- Use and [admission controller][0] to validate custom types
- CI/CD

[0]: https://kubernetes.io/docs/admin/extensible-admission-controllers/
