# TinyMLx edX (developing)

## Changes
- [3-7-11] Fixed data link.
- [3-5-18] Fixed tf1 -> tf2 compatibility issues (see [#16](https://github.com/tinyMLx/colabs/pull/16))
- [3-3-7] Fixed a typo in metadata. 


# TinyMLx edX 0.1.1 (2023-07-21)

## Changes
- [2-3-3] 
  - `from scipy import misc` --> `from scipy import datasets`
  - `misc.ascent()` --> `datasets.ascent()`
  - DeprecationWarning: scipy.misc.ascent has been deprecated in SciPy v1.10.0; 
    and will be completely removed in SciPy v1.12.0. Dataset methods have moved 
    into the scipy.datasets module. Use scipy.datasets.ascent instead.
- Fixed broken links in 2-x-x colabs. 
- In data links: `laurencemoroney-blog.appspot.com` --> `learning-datasets`
- [2-1-6] Only supports tf 2 and python 3.
- [2-1-4] Comments on the code maximum length is 80 characters.
- `fstring` is used for string formatting.
