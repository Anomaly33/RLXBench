# RLXBench
Requires python 3.11 and PlatEMO v4.2 (https://github.com/BIMK/PlatEMO). <br />
Clone this repository and install the packages specified in requirements.txt <br />
```
git clone https://github.com/oladayosolomon/RLXBench/
cd RLXBench
pip install -r requirements.txt
```
For the reacher environment, you'll need to install pybullet-gym from https://github.com/benelot/pybullet-gym<br />
```
git clone https://github.com/benelot/pybullet-gym.git
cd pybullet-gym
pip install -e .
```
you should then copy the DRL folder to the PlatEMO multi-objective problem directory, the mat_eval_env.py to the main PlatEMO directory (the one with the platemo.m file), and the HV_rl.m file to the Metric directory<br />

Path related information<br />

```
pyenv("Version",'C:\Users\ecis\anaconda3\envs\RL_Bench\python.exe')

```

create metric files for HV and Sparsity 


the following environments are currently implemented

| **Environment ID** | **Description**                |
|--------------------|--------------------------------|
| DRL1               | Deep Sea Treasure              |
| DRL2               | Deep Sea Treasure Concave      |
| DRL3               | Fruit Tree                     |
| DRL4               | Four Room                      |
| DRL5               | Fishwood                       |
| DRL6               | Minecart                       |
| DRL7               | Ant                            |
| DRL8               | Hopper                         |
| DRL9               | Half Cheetah                   |
| DRL10              | Reacher                        |
| DRL11              | Walker 2D                      |
| DRL12              | Lunar Lander                   |

If you find this code or project helpful in your research, please cite our paper:
```
@article{ajani2024deep,
  title={Deep reinforcement learning as multiobjective optimization benchmarks: Problem formulation and performance assessment},
  author={Ajani, Oladayo S and Ivan, Dzeuban Fenyom and Darlan, Daison and Suganthan, PN and Gao, Kaizhou and Mallipeddi, Rammohan},
  journal={Swarm and Evolutionary Computation},
  volume={90},
  pages={101692},
  year={2024},
  publisher={Elsevier}
}
```
