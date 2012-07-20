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

*color_sieve* prints on the standard output the hex value of the color(s) read from the given image file(s) matching the given constraints.

## Dependencies

python2, PIL and python-colormath.
