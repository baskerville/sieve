# color_sieve -- a python script to extract a palette from an image

![out_1](http://f.cl.ly/items/1R0T1L1T0g0m2r240B1U/output_20111120_124649.png)

## usage

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
            -M, --max-ab-distance-range <value>
                Upper bound for the ab-distance.
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
