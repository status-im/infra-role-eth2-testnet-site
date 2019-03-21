# Description

This role setups a nginx site hosting the Nimbus serenity [testnet metadata files](https://serenity-testnets.status.im).

# Installation

Add to your `requirements.yml` file:
```yaml
- name: eth2_testnet_site
  src: https://github.com/status-im/infra-role-eth2-testnet-site.git
```

# Requirements

Due to being part of Status infra this role assumes availability of certain things:

* Nginx full installation
