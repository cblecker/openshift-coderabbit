# OpenShift CodeRabbit Configuration

This repository contains the organization-wide [CodeRabbit configuration](https://docs.coderabbit.ai/configuration/central-configuration) for the `openshift` GitHub organization.

Rules and instructions defined here apply to most OpenShift repositories. Repository-specific overrides can be added in each repo's own `.coderabbit.yaml`.

## Using the org-wide config

To inherit this organization-level configuration, repositories must set `inheritance: true` in their `.coderabbit.yaml`:

```yaml
inheritance: true
```

See [openshift/sippy](https://github.com/openshift/sippy/blob/a24f31b0fc428f0f102680ebf8c8ccd74d64f2a3/.coderabbit.yaml#L1) for an example.

Without this setting, the org-wide configuration will not be applied.
