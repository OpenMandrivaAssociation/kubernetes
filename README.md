# Kubernetes

The Kubernetes rpm repository. Forthcoming Kubernetes releases will be available once the new release reaches release candidate stage or when the release reaches general availability.

Kubernetes releases are tracked at https://kubernetes.io/releases/ and is the canonical source for upstream lifecycle plans and status. Information in the table and paragraphs below may be dated. The golang version in the table below is the major:minor version used by upstream to build and test the release. The specific golang patch release used by Kubernetes can and will change.

| Kubernetes Version | Target Fedora Release | Kubernetes Planned End of Life | Golang Built With |
| :--- | --- | --- | ---: |
| 1.27 | F39 | 2024.06.28 | 1.20 |
| 1.26 | F38 | 2024.02.24 | 1.19*1 |
| 1.25 | F37 | 2023.10.27 | 1.19 |
| 1.24   | F36-EOL | 2023.07.28 | 1.18/1.19 |
| 1.23 | COPR-EOL | 2023.02.28 | 1.17, 1.19 |
| 1.22 | F35-EOL | 2022.10.28 | 1.16 |

*1 Expect the version of go used for 1.26 to change.
