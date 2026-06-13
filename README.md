# neuromaps

The [neuromaps toolbox](https://github.com/netneurolab/neuromaps) is designed to help researchers make easy, statistically-rigorous comparisons between brain maps (or brain annotations). Documentation can be found [here](https://netneurolab.github.io/neuromaps/).

The accompanying paper is published in [Nature Methods](https://www.nature.com/articles/s41592-022-01625-w) ([postprint](https://github.com/netneurolab/neuromaps/blob/main/markello2022natmethods.pdf)).

This repository contains a tutorial showing how to use neuromaps to contextualize results.

To run the demo, we recommend using miniconda/conda environment (you can install miniconda [here](https://www.anaconda.com/docs/getting-started/miniconda/main))

Then, on the command line, you can create a fresh environment:

```bash
conda create -n tutorial_env python=3.11
conda activate tutorial_env
```

And install the required packages (listed in requirements.txt)

```bash
pip install -r requirements.txt
```

Then, you can launch the notebook locally with:

```bash
python -m jupyter lab
```

# neuromaps - mouse

We're currently working on a spin-off of neuromaps, entirely focused on the mouse. It's currently under development but check it out: https://github.com/netneurolab/neuromaps-mouse

# netneurotools

Our lab also developed netenrutoools: a swiss army knife for network neuroscience. It consists of functions and routines that we often use but that are not part of any established pipeline or package. Check it out: https://github.com/netneurolab/netneurotools

# annotated connectomics

neuromaps is a great tool for annotated connectomics. See our recent review published in [Nature Reviews Neuroscience](https://www.nature.com/articles/s41583-023-00752-3)
