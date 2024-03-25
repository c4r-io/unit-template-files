
# unit-template-files

<!-- badges: start -->
<!-- badges: end -->

This repo contains example files to be used in setting up the project repos for units at Community for Rigor.

## Details

Individual files can be found in the `examples/` folder:

```
examples/
├── .zenodo.json
├── LICENSE.md
└── README.md
```

* `.zenodo.json` is the machine-readable metadata to accompany the deposition of units into the [Zenodo](https://zenodo.org/) repository.

* `LICENSE.md` defines the copyright and licensing permissions for the unit.

* `README.md` is the human-readable description of the unit.

## TODO

Create automation. Goals:

1. Most information in `.zenodo.json` and `README.md` should be auto-populated and updated from CENTER centralized data sources (unit roadmaps and/or other data about METER personnel)

2. Support customization in the following ways:

    a. sub-licensing of specific components in units (e.g. C4R has permission to use a particular figure or table, but cannot share that component with an open license)
    b. personal acknowledgments for a particular unit
