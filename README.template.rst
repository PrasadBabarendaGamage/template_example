

${example_name_header}
${example_name}
${example_name_header}

${short_description} ${long_description}

Building the example
====================

Instructions on how to configure and build with CMake::

  git clone https://github.com/OpenCMISS-Examples/${example_name}.git
  mkdir build
  cmake -DOpenCMISSLibs_DIR=/path/to/opencmisslib/install ../${example_name}
  make  # cmake --build . will also work here and is much more platform agnostic.

Running the example
===================

Explain how the example is run::

  cd build
  ./src/fortran/${example_name}.F90

or maybe it is a Python only example::

  source /path/to/opencmisslibs/install/virtaul_environments/oclibs_venv_pyXY_release/bin/activate
  python src/python/${example_name}.py

where the XY in the path are the Python major and minor versions respectively.

Prerequisites
=============

${external_sources}

License
=======

Apache 2.0 License
