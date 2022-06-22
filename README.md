# The poetry of Spikeinterface

This package integrates [spikeinterface](https://spikeinterface.readthedocs.io/en/latest/) into poetry packaging to ensure stability.

My personal experience is that installing `spikeinterface` is smoother this way.

## Installation

Run the following in shell:
```shell
pip install spikeinterface-poetry
```

You can install spikesorters such as `tridesclous`, `spyking-circus`, `herdingspikes`, `klusta`, `mountainsort` easily:
```shell
pip install spikeinterface-poetry[<spike sorter name>]
```
You can also install `phy`, `docker`, and `spython` (singularity) the same way as above.

## Important remarks

This package is maintained solely by me, and not the original authors of `spikeinterface`. Please don't make any issues related to the packaging in the `spikeinterface` repository. Should you have any problems running any of the spikesorters, contact the author of that spike sorter.

I also can't and don't guarantee that every component of spikeinterface to work as intended by the original authors. This is the nature of downstream packaging by a 3rd party. This should be less of an issue once poetry has been added to `spikeinterface`.
