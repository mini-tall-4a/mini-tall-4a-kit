# mini-tall-4a-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m mini_tall_4a_kit.cli --help
```

```python
from mini_tall_4a_kit.core import MiniTall4aTool

tool = MiniTall4aTool()
print(tool)
```

## Layout

```
mini_tall_4a_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 mini-tall-4a
