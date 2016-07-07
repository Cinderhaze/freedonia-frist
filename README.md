
# Rewrite needed....
# NIST-800-53 Standard
NIST-800-53 Standard Control for [Compliance Masonry](https://github.com/opencontrol/compliance-masonry)


To import these data into a OpenControl project add the follow code to your opencontrol.yaml file.
```yaml
dependencies:
  standards:
    - url: https://github.com/opencontrol/NIST-800-53-Standards
      revision: master
```

For more information on the opencontrol.yaml visit the [Compliance Masonry CLI](https://github.com/opencontrol/compliance-masonry#creating-an-opencontrol-project).
