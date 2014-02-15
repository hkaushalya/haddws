haddws
======

hadd with weights (or better hadd). Adds ROOT histograms split between files with given weights.

Download the package and build it using make.

Running the exectuable without arguments will spit instructions.

./haddws file1.root file2.root file3.root file1_weight file2_weight file3_weight


Note: If there are ROOT trees in the files, they will be simply merged ignoring the weights. There is no simple way to add trees with weights.

