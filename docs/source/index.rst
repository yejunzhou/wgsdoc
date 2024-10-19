Welcome to Wind Gate SDK's documentation!
===================================


The Ouster Sensor SDK provides developers interfaces for interacting with sensor hardware and
recorded sensor data suitable for prototyping, evaluation, and other non-safety-critical
applications in Python and C++. Example and reference code is provided for common operations on
sensor data in both languages. The SDK includes APIs for:

* Querying and setting sensor configuration
* Recording and reading data in pcap format
* Recording and reading data in Open Sensor Format (OSF)
* Reading and buffering sensor UDP data streams reliably
* Conversion of raw data to range/signal/near_ir/reflectivity images (destaggering)
* Efficient projection of range measurements to Cartesian (x, y, z) coordinates
* Visualization of multi-beam flash lidar data

Additionally, in Python, the SDK also provides:

* Frame-based access to lidar data as numpy datatypes
* A responsive visualizer utility for pcap and sensor


.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
