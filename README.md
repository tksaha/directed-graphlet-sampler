# Directed Graphlet Sampler

## Installation
To make executable, please run the following command under individual folder.

```
make
```

You can run the code in following way (In this version -undir should always be 1): 

```
./executablename -d [fileName] -i 100000 [iteration no] -s 4 [size] -q 1000 [queue size] -dir 1 
```

## Example Run and corresponding output

```
./motifMCMC-directed -d ../inputfile_maker_mcmcsampler/mal1_dir_graph.txt-mcmc-format  -i 1000 -s 3 -q 1000 -dir 1
#(0,1,1,1,1)(1,2,1,1,1)(2,0,1,1,1)-(0,0,1,)#4|0.004|
#(0,1,1,1,1)(1,2,1,1,1)-(0,0,)#118|0.118|
#(0,1,1,1,1)(1,2,1,1,1)-(1,0,)#256|0.256|
#(0,1,1,1,1)(1,2,1,1,1)-(0,1,)#622|0.622|

```




# Reference
If you are using the code for research purposes, please consider citing the following paper: 

```
@inproceedings{saha.hasan:15*2,
  title={Finding Network Motifs Using MCMC Sampling.},
  author={Saha, Tanay Kumar and Al Hasan, Mohammad},
  booktitle={CompleNet},
  pages={13--24},
  year={2015}
}
```

