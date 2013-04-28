![logo](https://github.com/baskerville/color_sieve/raw/master/preview/logo-color_sieve.png)

## Usage

    SYNOPSIS
            color_sieve [options] FILENAME ...
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

*color_sieve* prints to the standard output the hex representation of the colors read from the given image files satisfying the given constraints.

## Dependencies

- python3.
- Pillow.
- python-colormath.
