# OpenShift CodeRabbit Configuration

This repository contains the organization-wide [CodeRabbit configuration](https://docs.coderabbit.ai/configuration/central-configuration) for the `openshift` GitHub organization.

Rules and instructions defined here apply to most OpenShift repositories. Repository-specific overrides can be added in each repo's own `.coderabbit.yaml`.

## How it works

Repositories without their own `.coderabbit.yaml` automatically use this org-wide configuration. If a repository needs to add repo-specific settings, it must set `inheritance: true` in its `.coderabbit.yaml` to merge with the org-wide defaults — otherwise the repo-level config fully replaces them.

```yaml
inheritance: true
```

See [openshift/sippy](https://github.com/openshift/sippy/blob/a24f31b0fc428f0f102680ebf8c8ccd74d64f2a3/.coderabbit.yaml#L1) for an example.
