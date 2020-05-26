Installation / Contributing
============================================================================

.. toctree::
    :hidden:
    self

This package is still in development, so it can only be built from source. ::

    git clone https://github.com/epi-center/epi-center.git

epi-center requires a conda environment. Once you have a conda environment::

    conda env create -f environment.yml

Additionally, epicenter requires `grakn <https://grakn.ai/>`_. On mac::

    brew tap graknlabs/tap
    brew install graknlabs/tap/grakn-core

On other platforms, please refer to the `documentation <https://dev.grakn.ai/docs/running-grakn/install-and-run#system-requirements>`_.

In order to use jupyterlab, you'll need to enable the jupyterlab_code_formatter::

    jupyter serverextension enable --py jupyterlab_code_formatter