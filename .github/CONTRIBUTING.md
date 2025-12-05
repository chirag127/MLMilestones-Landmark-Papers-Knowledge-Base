# Contributing to MLMilestones-Landmark-Papers-Knowledge-Base

We are delighted that you're interested in contributing to **MLMilestones-Landmark-Papers-Knowledge-Base**, an AI-curated repository detailing landmark papers that shaped Machine Learning. Your expertise and contributions are invaluable in expanding this vital knowledge base.

By contributing, you agree to abide by our [Code of Conduct](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/blob/main/CODE_OF_CONDUCT.md).

## Table of Contents

- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Setting Up Your Development Environment](#setting-up-your-development-environment)
  - [Making Changes](#making-changes)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Coding Standards](#coding-standards)
- [Commit Guidelines](#commit-guidelines)
- [License](#license)

## How to Contribute

### Reporting Bugs

Encountered an issue? Please help us by reporting it thoroughly:

1.  Before submitting, check the [existing issues](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/issues) to see if your bug has already been reported.
2.  Open a new bug report using our dedicated [Bug Report template](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/blob/main/.github/ISSUE_TEMPLATE/bug_report.md).
3.  Provide clear, concise steps to reproduce the bug.
4.  Include expected vs. actual behavior, screenshots (if applicable), and your operating system/Python version details.

### Suggesting Enhancements

Have an idea for a new feature or improvement? We'd love to hear it:

1.  Check the [existing issues](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/issues) to ensure your suggestion hasn't been made already.
2.  Open a new issue. Clearly describe the enhancement, its potential benefits, and any proposed solutions.

### Setting Up Your Development Environment

To get started with local development, follow these steps:

1.  **Prerequisites:** Ensure you have Git and Python 3.10+ installed on your system.
2.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base.git
    cd MLMilestones-Landmark-Papers-Knowledge-Base
    
3.  **Create a Virtual Environment and Install Dependencies (using `uv`):**
    bash
    uv venv
    source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
    uv pip install -r requirements.txt --dev
    

    *Note: `uv` is our preferred package manager for its speed and reliability. Ensure you have it installed (`pip install uv`).*

4.  **Verify Setup:** Run the tests to ensure everything is configured correctly.
    bash
    pytest
    

### Making Changes

1.  **Create a New Branch:** Always create a new branch for your work. This keeps the `main` branch clean and simplifies pull requests.
    bash
    git checkout -b feature/your-feature-name # For new features
    git checkout -b fix/your-fix-name         # For bug fixes
    
2.  **Implement Your Changes:** Write your code, adhering to our [Coding Standards](#coding-standards).
3.  **Write Tests:** For every new feature or bug fix, corresponding unit and/or integration tests are mandatory using `pytest`.
4.  **Run Tests:** Ensure all existing and new tests pass.
    bash
    pytest
    
5.  **Lint and Format Your Code:** We use `Ruff` to enforce consistent code style and identify potential issues.
    bash
    ruff check . --fix
    ruff format .
    
6.  **Commit Your Changes:** Follow the [Commit Guidelines](#commit-guidelines).
    bash
    git add .
    git commit -m "feat: Add new paper entry for Transformers architecture"
    

### Submitting Pull Requests

1.  **Push Your Branch:**
    bash
    git push origin feature/your-feature-name
    
2.  **Open a Pull Request:** Navigate to the [repository on GitHub](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base) and open a new Pull Request. Ensure it's against the `main` branch.
3.  **Fill out the Template:** Our [Pull Request Template](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/blob/main/.github/PULL_REQUEST_TEMPLATE.md) will guide you through providing necessary information. Be thorough in describing your changes, their motivation, and how they were tested.
4.  **Address Feedback:** Our team will review your PR. Be prepared to address any feedback, suggestions, or requested changes.
5.  **CI/CD Pass:** Ensure that all Continuous Integration (CI) checks pass successfully. Your code will not be merged until all checks are green.

## Coding Standards

*   **Pythonic:** Adhere to Python best practices, including PEP 8 for style.
*   **Type Hinting:** Utilize Python's type hints (`typing` module) for improved readability and maintainability.
*   **Documentation:** All functions, classes, and complex logic blocks must be clearly documented with docstrings and inline comments where necessary.
*   **Modularity:** Follow principles of a Modular Monolith architecture, ensuring clear separation of concerns and maintainable code units.
*   **Linting & Formatting:** All code must pass `Ruff` checks without errors or warnings. Use `ruff check . --fix` and `ruff format .` before committing.

## Commit Guidelines

We enforce [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) to maintain a clear and searchable commit history. Each commit message should follow the pattern: `<type>(<scope>): <description>`.

**Examples:**

*   `feat: Add Transformer architecture landmark paper`
*   `fix(data): Correct typo in BERT paper author list`
*   `docs: Update contributing guidelines with uv usage`
*   `refactor(parser): Improve parsing logic for arXiv links`
*   `chore: Update uv dependencies`

## License

By contributing, you agree that your contributions will be licensed under the [CC BY-NC 4.0 License](https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/blob/main/LICENSE).