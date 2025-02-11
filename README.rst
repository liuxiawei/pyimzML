Attention
=======
This package is forked form the original package https://github.com/chhh/pyimzML (1.5.4, accessed in 20241025 ) and is modified with the aim to support the imzML format from Cardinal.
- support the the number displayed as e exponent (like 1e+9)
- ignore the the empty cv_param
pyimzML
=======

.. image:: https://readthedocs.org/projects/pyimzml/badge/?version=latest
    :target: http://pyimzml.readthedocs.org/en/latest/?badge=latest
    :alt: Documentation Status

Description
-----------
A parser for the imzML format used in imaging mass spectrometry. See specification
`here  <https://ms-imaging.org/wp-content/uploads/2009/08/specifications_imzML1.1.0_RC1.pdf>`_.
Designed for use with imzML version 1.1.0. Outputs data as python lists and dicts.

The parser is developed by `Alexandrov Team <https://www.embl.org/groups/alexandrov/>`_ at EMBL Heidelberg.

Installation
------------
pyimzML is available on `PyPI <https://pypi.python.org/pypi/pyimzML>`_. pyimzML
should be installed with pip using one of these three options:

* ``$ pip install pyimzml`` will install pyimzML from PyPI (easiest).
* ``$ pip install git+git://github.com/alexandrovteam/pyimzML.git`` will install pyimzML from github.
* Download the source tarball from `PyPI <https://pypi.python.org/pypi/pyimzML>`_ and ``$ pip install pyimzml-x-x-x.tar.gz``

**Dependency Notes**

* pyimzML has an optional dependency to `lxml <http://lxml.de/index.html>`_. If lxml is not installed, pyimzML will instead use the built-in cElementTree or ElementTree package.

**Testing**

To test your installation of pyimzML, you can download sample data from `imzml.org <https://www.ms-imaging.org/imzml/example-files-test/>`_ and run the tests.

Attribution
-----------

The pyimzml/ontology directory includes data derived from the following ontologies:

* `Units of measurement ontology <http://www.obofoundry.org/ontology/uo.html>`_ by George Gkoutos `CC-BY license <https://creativecommons.org/licenses/by/3.0/>`_
* `Mass spectrometry ontology <http://www.obofoundry.org/ontology/ms.html>`_ by `Gerhard Mayer et al. <https://pubmed.ncbi.nlm.nih.gov/23482073/>`_ `CC-BY license <https://creativecommons.org/licenses/by/3.0/>`_
* `Imaging MS controlled vocabulary <https://www.ms-imaging.org/imzml/controlled-vocabulary/>`_

Documentation
-------------

Documentation is available on `ReadTheDocs <http://pyimzml.readthedocs.org/en/latest/?badge=latest>`_
