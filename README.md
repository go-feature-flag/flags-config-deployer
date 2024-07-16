## Flags Config Deployer

[![Deploy to S3](https://github.com/go-feature-flag/flags-config-deployer/actions/workflows/deployer.yaml/badge.svg)](https://github.com/go-feature-flag/flags-config-deployer/actions/workflows/deployer.yaml)

This repository deploys configurations for GO Feature Flag to Amazon S3. 
Every commit merged to the `main` branch triggers a deployment, making the latest flag configuration available.

If a configuration is not valid the flag will be rejected.

---

_This repository is used to manage the internal instance of GO Feature Flag used by the GO Feature Flag team._
