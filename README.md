# An effective population-based  algorithm for the partial set covering problem
The executable file in this repository is the implementation of PSSC model, and the dataset is stored under data/.  
If this code helps with your studies, please kindly cite the following publication:
```python

```

## Usage
Run the provided executable file PSSC as follows: 
```python
./PSSC test_file_path cover_nums RandomSeed TimeLimit
```
test_file_path: the path of the data file used for testing.  
cover_nums: the number of elements covered by traditional Chinese medicine in the PSCP problem.  
RandomSeed: the random seed number
TimeLimit: the maximum running time of the program  
For Example:  
```python
./PSSC ./data/scp41.txt 190 1 100
```

