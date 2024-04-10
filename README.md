# Kuai_based_graph_data

We curated the Kuai dataset (https://kuairec.com/) and constructed it into a network dataset composed of video nodes. The construction process is as follows: we establish edges between videos based on the sequence of users browsing them. Then, each video is treated as a node, and the attribute information within the videos is considered as semantic information, resulting in a network structure dataset composed of videos.


### Original:
Datasets 𝐾𝑢𝑎𝑖𝑅𝑒𝑐_𝑆𝑝𝑎𝑟𝑠𝑒   

#Users 7,176    

#Videos 10,728    

#User-video 10,301,304   

#Video-video 12,521,016   

#Classes 30 

### After preprocessing:
graph.txt: nodeId nodeId

group.txt: classId nodeId

feature_bag_of_word.txt: classId [wordID:number]


### From Paper:
@inproceedings{chen2023zero,
  title={Zero-shot Micro-video Classification with Neural Variational Inference in Graph Prototype Network},
  author={Chen, Junyang and Wang, Jialong and Dai, Zhijiang and Wu, Huisi and Wang, Mengzhu and Zhang, Qin and Wang, Huan},
  booktitle={Proceedings of the 31st ACM International Conference on Multimedia},
  pages={966--974},
  year={2023}
}
