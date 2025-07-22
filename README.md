# Project Workflows

This project uses GitHub Actions workflows to automate issue and pull request management:

- **Issue Title Formatting**: New issues are automatically formatted to include a prefix and issue number, and assigned to the correct milestone.
- **TODO to Issue**: TODO comments in the codebase are automatically converted into GitHub issues labeled as `tech-debt`.
- **Copy Labels from Linked Issues**: Pull requests automatically inherit labels from their linked issues.

These workflows help maintain consistency and automate routine project management tasks.