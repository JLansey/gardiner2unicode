# gardiner2unicode: Mapping Egyptian Hieroglyphs

A Python3.6+ package that 
* provides a convenient out-of-the-box way to access the mapping 
of [Gardiner's Sign List](https://en.wikipedia.org/wiki/Gardiner%27s_sign_list) codes to unicode IDs;
* generates hieroglyphs as images.

A list of hieroglyphs was copied from 
[this Wikipedia template](https://en.wikipedia.org/w/index.php?title=Template:List_of_hieroglyphs&action=edit).

A 2.06 version of [NewGardiner font](https://mjn.host.cs.st-andrews.ac.uk/egyptian/fonts/newgardiner.html) is used
by default. Please note that since 2.05 its license is [OFL 1.1](https://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web).

One can use any other font with `UnicodeGlyphGenerator`.

## Installation

    pip install -U gardiner2unicode

## Usage example

```python
from gardiner2unicode import GardinerToUnicodeMap
g2u = GardinerToUnicodeMap()
print(g2u.to_unicode_hex("A1"))
```

## How to cite

Please cite this repository if you use this work in your research.

```bibtex
@misc{gardiner2unicode2021alekseev,
  title     = {{alexeyev/gardiner2unicode: Mapping Egyptian Hieroglyphs}},
  year      = {2021},
  url       = {https://github.com/alexeyev/gardiner2unicode},
  language  = {english}
}
```

## Links

* [NewGardiner font](https://mjn.host.cs.st-andrews.ac.uk/egyptian/fonts/newgardiner.html)
* [Gardiner's Sign List](https://en.wikipedia.org/wiki/Gardiner%27s_sign_list)