# anthropic-course-code

Hands-on notebooks from Anthropic's API course, written while preparing for the
**Claude Certified Associate (CCA)** exam. Each notebook builds on the previous one
and demonstrates one core capability of the Anthropic Messages API using the
official Python SDK.

## Setup

1. **Requirements:** Python 3.9+ and Jupyter.

2. **Install dependencies:**

   ```bash
   pip install anthropic python-dotenv
   ```

3. **API key:** create a `.env` file in the project root (it is git-ignored):

   ```env
   ANTHROPIC_API_KEY=sk-ant-...
   ```

   `load_dotenv()` picks the key up automatically, so the `Anthropic()` client
   needs no extra configuration.

4. **Run:** open any notebook in Jupyter / VS Code and execute the cells top to bottom.

## License

[MIT](LICENSE)
