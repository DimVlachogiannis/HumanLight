# Introduction
This repo includes the implementation of HumanLight, a decentralized adaptive signal control algorithm that is person-based and founded on reinforcement learning in the context of network level control.

This repo is built on top of LibSignal (https://github.com/DaRL-LibSignal/LibSignal.git) which provides OpenAI Gym compatible environments for traffic light control scenario and a bunch of baseline methods.

At this moment, HumanLight can only be implemented via CityFlow. Future maintaining plan includes merging HumanLight into the LibSignal library.

# Configurations 
### Single Intersection <br />
Low HOV Adoption: 1x1>flow_config28.json  <br />
Light HOV Adoption: 1x1>flow_config29.json  <br />
Moderate HOV Adoption: 1x1>flow_config30.json <br />
High HOV Adoption: 1x1>flow_config31.json <br />

### 1x6 Corridor <br />
Low HOV Adoption: arterial_1x6>flow_config40.json <br />
Light HOV Adoption: arterial_1x6>flow_config41.json <br />
Moderate HOV Adoption: arterial_1x6>flow_config42.json <br />
High HOV Adoption: arterial_1x6>flow_config43.json <br />

### 4x4 Grid <br />
Low HOV Adoption: grid_4x4>flow_config20.json <br />
Light HOV Adoption: grid_4x4>flow_config21.json <br />
Moderate HOV Adoption: grid_4x4>flow_config22.json <br />
High HOV Adoption: grid_4x4>flow_config23.json <br />


# Citation
When using this repo, please cite the preprint that has been submitted to Elsevier for publication and is available at
https://arxiv.org/abs/2304.03697 ,and can be cited with the following bibtex entry: <br />

```
@misc{vlachogiannis2023humanlight,
      title={HumanLight: Incentivizing Ridesharing via Human-centric Deep Reinforcement Learning in Traffic Signal Control}, 
      author={Dimitris M. Vlachogiannis and Hua Wei and Scott Moura and Jane Macfarlane},
      year={2023},
      eprint={2304.03697},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```


Please also cite the whitepaper of LibSignal accepted by NeurIPS 2022 Workshop: Reinforcement Learning for Real Life is available https://arxiv.org/abs/2211.10649, and can be cited with the following bibtex entry:

```
@misc{2211.10649,
  Author = {Mei, Hao and Lei, Xiaoliang Lei and Da, Longchao Da and Shi, Bin and Wei, Hua},
  Title = {LibSignal: An Open Library for Traffic Signal Control},
  Year = {2022},
  booktitle={NeurIPS Workshop on Reinforcement Learning for Real Life},
}
```
