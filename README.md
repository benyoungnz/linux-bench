

### Run example
```bash
sudo wget https://raw.githubusercontent.com/benyoungnz/linux-bench/master/linux-bench-minimal.sh && chmod +x linux-bench-minimal.sh && ./linux-bench-minimal.sh
```

### Changes made from STH version
- Removal of other linux distributions, intended to be run from Ubuntu
- Not submitting report data to linux-bench.com
- Updated package references from linux-bench.com to Github 

		
### About original project
	This has been forked from:  https://github.com/STH-Dev/STHbench.sh
		
 	Linux-Bench - A System Benchmark and comparison tool created by the STH community adapted by Ben Young.

	Linux-Bench is a sscript that runs hardinfo, Unixbench 5.1.3, c-ray 1.1, STREAM, OpenSSL, sysbench (CPU),
	crafty, redis, NPB, NAMD, and 7-zip benchmarks
	
	Linux-Bench must be run as root or using a su prompt to automate download and installation of benchmarks
	If running in a virtual environment, export VIRTUAL=TRUE before running. Automatically set for Docker.

   	Original Authors: Patrick Kennedy, Charles Nguyen (Chuckleb), Patriot, nitrobass24, mir  
