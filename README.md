# SBOM Observer CycloneDX Property Taxonomy

This is the CycloneDX property taxonomy for SBOM Observer. It documents key/value properties that may be exported by SBOM Observer in CycloneDX SBOMs.

For more information about SBOM Observer see https://sbom.observer

For more information about CycloneDX, see https://cyclonedx.org.

## `observer:` namespace taxonomy

| Scope | Property | Description |
| -------- | -------- | -----------  |
| BOM | `observer:organization:id` | The organization id used to create the SBOM |
| BOM | `observer:namespace:id` | The namespace id used to create the SBOM |
| Component | `observer:source:url` | The url for the attestation that first imported the component in to the namespace |
| Component | `observer:attestation:original:purl` | The original [Package ULR](https://github.com/package-url/purl-spec) for a component that was imported into a namespace from an SBOM |