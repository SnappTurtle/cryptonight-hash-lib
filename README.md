# cryptonight-hash-lib

Copyright (c) 2017, Sumokoin.org

This a python-wrapper lib to give cryptonight hashing functions for Sumo Easy Miner

To complile on Linux:

	cd /path/to/cryptonight-hash-lib
	cmake . -DPYTHON_INCLUDE_DIR=$(python -c "from distutils.sysconfig import get_python_inc; print(get_python_inc())")  -DPYTHON_LIBRARY=$(python -c "import distutils.sysconfig as sysconfig; print(sysconfig.get_config_var('LIBDIR'))")
	make
