# CommunityDetectionCodes
Locality-Based Overlapping Community Detection Algorithms. 
And I recommend you to use jetbrains' ide namely clion, pycharm and intellij to 
read related codes. 

Some Non-Overlapping Community Detections Algorithms could be found in [NonOverlappingCodes](NonOverlappingCodes).

I also write a community-detection survey in [Survey](Survey), you can have a look, if interested. 

##Algorithms

In each algorithm, there is a `ReadMe.md`, which gives brief introduction of corresponding information of the algorithm and 
current refactoring status. All c++ projects are built with `cmake`, java projects are built with `maven`, python projects 
are not specified how to build.

Algorithm | Implementation Language | Dependency | Refactor Status
--- | --- | --- | ---
[2009-Connected-Iterative-Scan](2009-Connected-Iterative-Scan) | c++ |  | build success
[2009-EAGLE](2009-EAGLE) | c++ | igraph, boost | build success
[2010-LinkComm](2010-LinkCommunity) | python|  |
[2010-iLCD](2010-iLCD) | java | args4j, trove4j | build success
[2010-CONGA](2010-CONGA) | java | | only jar-files now
[2011-GCE](2011-GCE) | c++ | boost | build success
[2011-OSLOM-v2](2011-OSLOM-v2) | c++ | |
[2011-SLPA](2011-SLPA) | python | networkx, numpy |
[2012-DEMON](2012-DEMON) | python | networkx | python okay
[2013-Seed-Set-Expansion](2013-Seed-Set-Expansion) | c++, matlab | graclus, matlabgl | 
[2014-Heat-Kernel](2014-Heat-Kernel) | c++, matlab, python | pylibbvg | python okay
[2015-LEMON](2015-LEMON) | python | pulp | python okay

##Submodules(Dependencies)

Detailed information is in [SubModules](SubModules).

Submodule | Implementation Language
--- | ---
[igraph](https://github.com/igraph/igraph) | c
[Graclus](https://github.com/GraphProcessor/Graclus) | c++

##Benchmarks

Content | Detail
--- | ---
[2009-LFM-Benchmark](2009-LFM-Benchmark) | LFM Benchmark to generate five types of graphs

##Scripts

Some file processing utility python scripts are put in [Scripts](Scripts).

##DataSets

Detailed information is in [Datasets](Datasets).

##Attention
These codes are all research codes, which I found through the internet. Please do not use them in production enviroment.
