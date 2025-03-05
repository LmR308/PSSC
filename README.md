# An effective population-based  algorithm for the partial set covering problem

The executable file in this repository is the implementation of PSSC model, and the dataset is stored under data/.  
If this code helps with your studies, please kindly cite the following publication:

```
@article{zhang2025effective,
  title={An effective population-based approach for the partial set covering problem},
  author={Zhang, Ye and He, Jinlong and Zhou, Yupeng and Hu, Shuli and Cai, Dunbo and Tian, Naiyu and Yin, Minghao},
  journal={Journal of Heuristics},
  volume={31},
  number={1},
  pages={1--32},
  year={2025},
  publisher={Springer}
}
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
