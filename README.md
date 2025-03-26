# Organization-wide GitHub Templates

This repository contains standardized GitHub templates (including issue and pull request templates) that are automatically available across all repositories in our organization.

## What's Included

This repository provides organization-wide GitHub templates for:

- [Bug reports]([.github/ISSUE_TEMPLATE/bug_report.md](https://github.com/Arete-Innovations/.github/blob/main/.github/ISSUE_TEMPLATE/%20bug_report.md))
- [Feature requests]([.github/ISSUE_TEMPLATE/feature_request.md](https://github.com/Arete-Innovations/.github/blob/main/.github/ISSUE_TEMPLATE/feature_request.md))
- [Pull request template](https://github.com/Arete-Innovations/.github/blob/main/.github/pull_request_template.md)

## How It Works

When contributors open an issue in any repository within our organization, they will be prompted to choose from these templates, ensuring consistent issue reporting and easier triage across all our projects.

## Repository Structure

```
.github/
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md
    │   └── feature_request.md
    └── pull_request_template.md

```

**Note:** The unusual double `.github` folder structure is intentional and required for organization-wide templates to work correctly.

## Setup Notes

This implementation follows a workaround for organization-wide templates that requires the double `.github` directory structure:

```
Arete-Innovations/.github/.github/ISSUE_TEMPLATE/bug_report.md
```

While GitHub documentation suggests templates should be at the root of the `.github` repository, this approach ensures templates are properly applied across all repositories in the organization.

## Future Templates

We plan to expand our template collection in the future. Potential templates to consider adding:

1. **Documentation Update Template** - For changes to documentation that don't involve code
2. **Security Vulnerability Report** - With appropriate confidentiality controls
3. **Performance Issue Template** - For reporting performance bottlenecks
4. **Dependency Update Request** - For suggesting library or dependency upgrades
5. **UI/UX Improvement Suggestion** - For design-related enhancements
6. **Release Checklist** - For standardizing the release process

## Resources

- [GitHub Documentation on Issue Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
- [About YAML Frontmatter in Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms)

## Contributing

To modify these organization-wide templates, please submit a pull request to this repository.
