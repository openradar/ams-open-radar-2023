<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Norman_Doppler_Radar_-_NOAA.jpg/640px-Norman_Doppler_Radar_-_NOAA.jpg" alt="thumbnail" width="300"/>

# AMS Open Radar Short Course 2023

[![nightly-build](https://github.com/openradar/ams-open-radar-2023/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/openradar/ams-open-radar-2023/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.projectpythia.org/badge_logo.svg)](http://binder.projectpythia.org/v2/gh/openradar/ams-open-radar-2023/main?labpath=notebooks)
[![ARM Jupyterhub Badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=ARM+JupyterHub&message=Workshop&color=blue)](https://jupyterhub-workshop.svcs.arm.gov/)


## Motivation

This content will be used for the Open Radar Short Course held at the AMS Radar Meeting. It will detail how to get started with the Open Radar stack, focusing on a few key scientific workflows.

## Authors

Open Radar Community Members

### Contributors

<a href="https://github.com/openradar/ams-open-radar-2023/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=openradar/ams-open-radar-2023" />
</a>

## Structure


### Foundational Tools

There are some foundational tools, such as xradar, wradlib, LROSE, and Py-ART!

|       Time          |    Content                                        | Speaker/Chair | Duration   |
|    :---:            |    :----:                                         |    :---:      | :----:     |
| 08:00 AM - 08:30 AM | Overview of the Open Radar Community + Tools      | Max Grover    | 30 minutes |
| 08:30 AM - 08:45 AM | Intro to xradar                                   | Max Grover    | 15 minutes |
| 08:45 AM - 09:30 AM | Hands on with Py-ART                              | Joe O'Brien   | 45 minutes |
| 09:30 AM - 10:00 AM | Hands on with Pyrad                               | Jordi Figueras i Ventura and Daniel Wolfensberger |  30 minutes  |
| 10:00 AM - 10:30 AM | Coffee Break                                      |               | 30 minutes |
| 10:30 AM - 11:15 AM | Hands on with wradlib                             |  Julian Giles | 45 minutes |
| 11:15 AM - 12:00 PM | Hands on with LROSE wind tools                    | Jen DeHart + Ting-Yu Cha | 45 minutes |
| 12:00 PM - 01:15 PM | LUNCH                                             |               | 1 hour 15 minutes |

### Analysis-Specific Tools

There are some analysis-specific tools, such as PyDDA, MetPy, and TOBAC!

|       Time          |    Content                                        | Speaker/Chair | Duration   |
|    :---:            |    :----:                                         |    :---:      | :----:     |
| 01:15 PM - 02:00 PM | Multi-Doppler Analysis with PyDDA                 | Bobby Jackson | 45 minutes |
| 02:00 PM - 02:45 PM | Tracking Cells with TOBAC                         | Sean Freeman + Kelcy Brunner | 45 minutes |
| 02:45 PM - 03:30 PM | Visualizing other Observations and Models with Radar using MetPy | Ryan May and Drew Camron | 45 minutes |
| 03:30 PM - 04:00 PM | Hands on with BALTRAD                             | Daniel Michelson   | 30 minutes |


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
