# Storage Costs Evaluator

[![Storage Costs Evaluator CI](https://github.com/ds-wizard/storage-costs-evaluator/workflows/Storage%20Costs%20Evaluator%20CI/badge.svg)](https://github.com/ds-wizard/storage-costs-evaluator/actions)
[![License](https://img.shields.io/github/license/ds-wizard/storage-costs-evaluator.svg)](LICENSE)
[![Docker Pulls](https://img.shields.io/docker/pulls/datastewardshipwizard/storage-costs-evaluator.svg)](https://hub.docker.com/r/datastewardshipwizard/storage-costs-evaluator/)

Simple JSON service for evaluating costs long-term data storage. Calculation made by Rob Hooft for DTLS.nl (@rwwh).

## Install and run

```console
stack build
npm install
npm run-script build
stack exec storage-costs-evaluator
```

## License

This project is licensed under the MIT license - see the [LICENSE](LICENSE) file for more details.
