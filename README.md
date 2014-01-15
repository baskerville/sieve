![logo](https://github.com/baskerville/sieve/raw/master/preview/logo-sieve.png)

## Usage

    SYNOPSIS
            sieve [options] FILENAME ...
    OPTIONS
            -h, --help
                Show this message.

            -n, --num-colors NUM
                Generates NUM colors.

            -L, --lightness-range MIN-MAX
                Discard colors outside of the given lightness range.

            -C, --chroma-range MIN-MAX
                Discard colors outside of the given chroma range.

            -H, --hue-range MIN-MAX
                Discard colors outside of the given hue range.


## Description

*sieve* prints to the standard output the hex representation of the colors read from the given image files satisfying the given constraints.

## Dependencies

- python3.
- Pillow.
- python-colormath.
