# Contributing to Multerm

Thank you for your interest in contributing to **Multerm**! We welcome contributions from developers and the community. This guide ensures your contributions are safe, organized, and properly credited while keeping the project secure, collaborative, and aligned with its goals.

## Workflow & Branching

Use the following **branch naming conventions**:

- `feature/<description>` – For new features or major improvements  
- `bug/<description>` – For bug fixes related to a feature or development branch  
- `hotfix/<description>` – For urgent fixes on the current release / `main` branch  

> Always create a new branch from the branch you intend to target (e.g., `main` for hotfixes, `develop` or `main` for features/bugs).

## Making Changes

- Follow **C# and Avalonia MVVM best practices**:  
  - Organize Models, ViewModels, Views, and Services logically  
  - Maintain clear, readable, and commented code  
- Ensure **consistent formatting and indentation**  
- Avoid committing large binaries or unrelated files  
- **Track contributors per file**: Each modified file should include the username of the contributor, their GitHub link, and a short note on their changes (bugfix, feature, etc.)

> The core plugin system is part of the main codebase and follows normal contribution rules. Plugins themselves can be contributed separately or developed independently.


## Testing

- Any new feature, bug fix, or update **must be tested by the contributor**.  
- Verify that changes **do not break existing functionality or introduce vulnerabilities**.  
- Include testing notes or screenshots in your Pull Request if relevant.  

> Contributors are responsible for the safety and stability of their changes.


## Pull Requests

1. Push your branch to your fork:

```bash
git push origin feature/my-awesome-feature
```

Open a Pull Request (PR) against the official repository.

Include a detailed description of:
- Changes made
- Reason for the changes
- Testing performed, screenshots, or examples

Only PRs merged into the official repository become part of the official Multerm client.

## Forks & Unofficial Builds

Forks are allowed for personal development, testing, or contributions.
Unofficial forks cannot use official branding (name, logo, or website).
Only merged contributions in the official repo become “official.”

## Communication

For larger features or architectural changes, open an issue first for transparency and discussion.
Small fixes or minor enhancements can be submitted directly via Pull Requests.
Email is acceptable, but using GitHub issues is preferred to allow community discussion and feedback.

## Plugins

The core plugin system is part of the main repository and contributed like normal code.
Community or private plugins can be developed independently and do not require submission to the main repository.
Official plugin listings will be curated in the main repository or approved community directories.

## Acknowledgment & Ownership

By submitting contributions, you agree that the code becomes the property of DigiQuan and may be included in the official Multerm project.
Contributors are credited per file with their GitHub profile and a description of their contribution (bugfix, feature, etc.).
Thank you for helping make Multerm better! Your contributions are appreciated and recognized.