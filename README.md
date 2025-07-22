# Project Workflows

This project uses GitHub Actions workflows to automate issue and pull request management:

- **Issue Title Formatting & Milestone Assignment**: Issues are automatically formatted with a prefix and number, and assigned to milestones based on their content.
- **TODO Comment Detection**: TODO comments in the codebase are detected and converted into GitHub issues labeled as `tech-debt`.
- **Pull Request Label Inheritance**: Pull requests inherit labels from their linked issues for consistent tracking.
- **Pull Request Validation**: Automated checks ensure pull requests meet project requirements before merging.
- **Automated Status Checks**: Status updates and validations are performed automatically on pull requests.

These workflows help maintain consistency and automate routine project management tasks.