# Epicenter
[![jogl](https://img.shields.io/static/v1?label=join%20us%20on&message=JOGL&color=red&link&style=flat-square)](https://app.jogl.io/project/169)
[![license](https://img.shields.io/github/license/understand-covid/proposal?style=flat-square)](https://github.com/understand-covid/proposal/blob/master/LICENSE)

Epicenter is a work in progress.

Epicenter is a knowledge-based system for computational epidemiology, focused on infectious disease spread. It combines a robust ontology of parameters that are useful for a broad variety of models with a knowledge graph containing data that pertains to specific diseases.

Epicenter aims to first provide modeling around COVID-19/SARS-CoV2. Documentation of the current work in progress is available in the [docs](https://epi-center.rtfd.io).

## Installation:

Epicenter requires a conda environment. Once you have a conda environment, run the following:

```
conda env create -f environment.yml
```

Additionally, epicenter requires [grakn](https://grakn.ai/). On mac, run the following

```
brew tap graknlabs/tap
brew install graknlabs/tap/grakn-core
```

On other platforms, please refer to the [documentation](https://dev.grakn.ai/docs/running-grakn/install-and-run#system-requirements).

In order to use jupyterlab, you'll need to enable the jupyterlab_code_formatter:

`jupyter serverextension enable --py jupyterlab_code_formatter`


## Contact / Collaboration

  If you are interested in collaborating or helping fund this project:

[![email](https://img.shields.io/static/v1?label=email&message=johnurbanik@gmail.com&color=red&&style-flat-square)](mailto:johnurbanik@gmail.com)
[![twitter](https://img.shields.io/twitter/follow/johnurbanik?label=%40johnurbanik&style=flat-square)](https://twitter.com/johnurbanik)
[![jogl](https://img.shields.io/static/v1?label=join%20us%20on&message=JOGL&color=red&link&style=flat-square)](https://app.jogl.io/project/169)