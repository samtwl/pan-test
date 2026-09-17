# Contributing to pan-test

Thanks for your interest in contributing! pan-test is a small Python project for experimenting with pandas and NumPy, and contributions of any size are welcome, whether that's a bug fix, a new notebook, or a documentation tweak.

## Getting started

1. Fork the repository and clone your fork.
2. Create a virtual environment and install the dependencies:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

3. Check that everything runs:

   ```bash
   python main.py
   ```

## Making changes

- Create a branch off `main` for your work.
- Keep changes small and focused, with clear commit messages.
- If you add a dependency, pin it in `requirements.txt`.
- Clear notebook outputs before committing unless they are part of the point.

## Submitting a pull request

Open a pull request against `main` with a short description of what changed and why. If you're unsure about an idea, open an issue first to discuss it.
