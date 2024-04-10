# Kuai_based_graph_data

We curated the Kuai dataset (https://kuairec.com/) and constructed it into a network dataset composed of video nodes. The construction process is as follows: we establish edges between videos based on the sequence of users browsing them. Then, each video is treated as a node, and the attribute information within the videos is considered as semantic information, resulting in a network structure dataset composed of videos.


# Datasets     #Users   #Videos   #User-video   #Video-video  #Classes 
𝐾𝑢𝑎𝑖𝑅𝑒𝑐_𝑆𝑝𝑎𝑟𝑠𝑒  7,176    10,728     10,301,304    12,521,016   30 

# After preprocessing
graph.txt: nodeId nodeId
group.txt: classId nodeId
feature_bag_of_word.txt: classId [wordID:number]


