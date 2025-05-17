# Doramas-AI-Technical-Assessment

This repository contains a technical assessment focused on sentiment analysis of movie reviews.

## Environment Setup

For this project, I decided to support the enviroment setup using [uv](https://github.com/astral-sh/uv), an extremely fast Python package manager. This improves reproducibility and ease of setup across systems.

### 1. Install uv

#### Windows:

- **uv**: it provides a standalone installer to download and install uv:

  ```<sh>
  powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
  ```

#### macOS/linux

- **Uv** is a single command line executable. There are a number of ways to install it, but the easiest is to use the provided installation script:

  ```<sh>
  curl -LsSf https://astral.sh/uv/install.sh | sh
  ```

### 2. How to Use It

#### Install Dependencies and Create a Virtual Environment

From the project root:

```console
$ uv sync
```

This will create a virtual environment and install all required packages automatically.

## Optional Enhancements

**Note:** In a typical development workflow, I usually like to integrate tools like ruff and mypy to ensure code quality and type safety. I generally include these checks as GitHub Actions, configured to run automatically on every pull request.

For this assessment, I’ve focused on the core functionality, as I felt adding those tools would be overengineering. However, they can be easily integrated if needed.