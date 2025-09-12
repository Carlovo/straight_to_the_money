# Straight to the Money 💰

> _Minimalistic yet all-inclusive Python project template_

Stop wasting time in analysis paralysis over Python tooling choices 💸  
Pick the defaults 💱  
Go straight to the money 💹

This template focusses on simplicity.
If you want something more robust, check this project's detached fork: [Paleofuturistic Python](https://github.com/schubergphilis/paleofuturistic_python).

## Usage

Prerequisite: [uv](https://docs.astral.sh/uv/)  
(Installing uv should also provide you with uvx.
Give their docs a look-over before continuing if you want to get a better understanding of what is going on under the hood in the steps below.)

### Setup

- Initialize with `uvx cruft create https://github.com/Carlovo/straight_to_the_money` and fill in your project details.
- Validate the setup with `uv run python -c "import straight_to_the_money; print(straight_to_the_money.hello())"` (replace `straight_to_the_money` with your project name/slug).
- Optionally, pull in any dependencies with `uv add some_lib_you_need`

### Workflow

- Develop (optional, tinker: `uvx --with . ptpython`)
- QA:
    - Format: `uvx ruff format`
    - Lint: `uvx ruff check`
    - Test: `uv run python -m unittest`
- Build: `uv build`
- Document: `uvx mkdocs build`
- Publish: `uv publish`

Can it really be that simple?
Well, eventually yes, but you will need to set up some connections and credentials still, of course.
For a slightly more elaborate walkthrough on that, see the [docs](https://carlovo.github.io/straight_to_the_money/walkthrough/).

Still skeptical?
See the [about](https://carlovo.github.io/straight_to_the_money/about/) instead.
Or, have a look at [my kitchen sink project](https://github.com/Carlovo/straight_to_the_kitchen_sink) created with this template.
