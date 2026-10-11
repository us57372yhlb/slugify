# slugify

Transliterates and normalises text into slugs suitable for URLs and filenames.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install slugify
```

## Usage

```python
from slugify import slugify

result = slugify("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
