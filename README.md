# project

The files corresponding to inclusive, non-inclusive and exclusive implementations have been kept in ChampSim folder. The corresponding files are inc_cache.cc, non-inc-cache.cc and exc-cache.cc respectively.
Each of these files is to be sent to src folder separately and renamed to cache.cc for each implementation. 

Following commands are to be run in ChampSim folder for the same -

For inclusive
`cp inc_cache.cc ./src/cache.cc`
For non-inclusive
`cp non-inc-cache.cc ./src/cache.cc`
For exclusive
`cp exc-cache.cc ./src/cache.cc`

For building run the following command inside ChampSim folder
`./build_champsim.sh bimodal no no no no [replacement policy] [num_cores]`

For running use following command inside ChampSim folder
`./run_champsim.sh [binary] 30 30 [trace] [option]`

results_30M folder will contain all the result files.

traces are inside dpc3_traces folder
