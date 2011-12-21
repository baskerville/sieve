![logo](http://blobs.ge.tt/4EcnB8B/color_sieve_logo.png?sig=-TRh30DsPgF0LlWwjayIW4AR5-ZvzWAsDa8)


    SYNOPSIS
            color_sieve [options] <image>
    OPTIONS
            -h, --help
                Show this message.

            -o, --output <name>
                Save the generated palette to <name>.

            -s, --size <num>
                Generates a palette of <num> colors.

            -l, --luminances <list>
                Generates colors for each luminance in <list>.

            -m, --min-ab-distance <value>
                Lower bound for the ab-distance.

            -M, --max-ab-distance <value>
                Upper bound for the ab-distance.

            -n, --norm-range <min-max>
                Colors which ab-norm isn't in the given range are discarded.

            -u, --luminance-range <min-max>
                Colors which L*a*b* luminance isn't in the given range are discarded.

            -r, --square-side <length>
                Set the side <length> in pixels of the output squares.

            -p, --pulse-every <value>
                If verbose mode is activated, show remaining pixels every <value> pixels.

            -k, --keep-luminance
                Keep original luminance in the output.

            -z, --solarized-luminances
                Use luminance values taken from the 'solarized' scale.

            -v, --verbose-progress
                Show informations about the palette while it's being generated.


## Dependencies

python2, PIL and python-colormath.

## Algorithm

The following iteration is performed until the number of colors in the palette is superior or equal to `size` or if all the pixels in the input image are exhausted:

- One random color is picked from the input image
- If its euclidean ab-distance to the palette is superior to `min_ab_distance` (and inferior to `max_ab_distance`) or if the palette is empty, then the color is added to the palette.

## Color Exploration Tools

gpick.
