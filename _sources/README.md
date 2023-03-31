<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Norman_Doppler_Radar_-_NOAA.jpg/640px-Norman_Doppler_Radar_-_NOAA.jpg" alt="thumbnail" width="300"/>

# AMS Open Radar Short Course 2023

[![nightly-build](https://github.com/openradar/ams-open-radar-2023/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/openradar/ams-open-radar-2023/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.mypythia.org/badge_logo.svg)](http://binder.mypythia.org/v2/gh/openradar/ams-open-radar-2023/main?labpath=notebooks)


## Motivation

This content will be used for the Open Radar Short Course held at the AMS Radar Meeting. It will detail how to get started with the Open Radar stack, focusing on a few key scientific workflows.

## Authors

[First Author](@first-author), [Second Author](@second-author), etc. _Acknowledge primary content authors here_

### Contributors

<a href="https://github.com/openradar/ams-open-radar-2023/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=openradar/ams-open-radar-2023" />
</a>

## Structure


### Foundational Tools

There are some foundational tools, such as xradar, wradlib, and Py-ART!

### Analysis-Specific Tools

There are some analysis-specific tools, such as PyDDA!

## Running the Notebooks

You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/openradar/ams-open-radar-2023` repository:

   ```bash
    git clone https://github.com/openradar/ams-open-radar-2023.git
   ```

1. Move into the `ams-open-radar-2023` directory
   ```bash
   cd ams-open-radar-2023
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate ams-open-radar-2023-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
