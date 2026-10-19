# Salesforce Data 360 Project Instructions

- Keep Salesforce metadata under `force-app/main/default/` and use Salesforce DX source format.
- Add only Data 360 metadata and configuration requested for the specific org and use case; do not assume data sources, data model objects, mappings, identity resolution rules, or activation targets.
- Keep org-specific credentials and environment values out of source control.
- Update `manifest/package.xml` when adding metadata intended for manifest-based deployment or retrieval.
- Validate changes with available Salesforce CLI commands. Org-dependent validation requires an authorized org with Data 360 enabled.
