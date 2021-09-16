# POC phoronix data extraction

The phoronix test suite is a benchmarking tool developped by Michael Larabel, that can be used to measure the performances of your environment (os, hardware, etc.).
Additionally, you can send the results of your benchmarking to a website, namely openbenchmarking.org, and compare your results with others.
The website allows you to compare performances depending on the processor or the version of the operating system you used, for a wide range of (versions of) software systems.

Thanks to this huge collaborative work, there now exists a big database of measurements, computed in the same conditions for each environment. 
However, and to the best of our knowledge, there is no obvious way to download all the raw data, cf this [first issue](https://github.com/phoronix-test-suite/openbenchmarking/issues/7) and this [second issue](https://github.com/phoronix-test-suite/phoronix-test-suite/issues/146).
As a user, it is probably enough to see a simple table to draw conclusions about your system. 
But as researchers, it is not possible to systematically compare the results with each others until we get the raw data.
This would be an incredible contribution to research if made usable (for instance in the performance/variability communities).

There were some attempts e.g. [this one](https://github.com/davidovitch/python-pts-openbenchmarking/) but no fast and obvious way to get all the xml files.

Is it yet possible to extract all the measurements of openbenchmarking.org? And if yes, how?


