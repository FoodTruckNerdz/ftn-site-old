# Documentation Folder

This `docs/` folder is an Antora documentation component for the legacy website.

## Structure

- `antora.yml` - Component descriptor (defines component name and version)
- `modules/` - Documentation modules (typically ROOT)
  - `modules/ROOT/pages/` - AsciiDoc documentation pages
  - `modules/ROOT/nav.adoc` - Navigation structure

## Antora Integration

This documentation is aggregated into the unified FoodTruckNerds documentation site via the playbook in the [docs repository](https://github.com/FoodTruckNerds/docs).

Published site: https://foodtrucknerds.github.io/docs
