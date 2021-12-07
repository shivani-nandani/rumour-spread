# rumour-spread
analysis of rumor spread in complex social networks using multiple parameters - trust mechanism, hibernation and counterattack. 

## dataset(s):
### [Social circles: Facebook](http://snap.stanford.edu/data/ego-Facebook.html)
Link - http://snap.stanford.edu/data/facebook_combined.txt.gz

This dataset consists of 'circles' (or 'friends lists') from Facebook. Facebook data was collected from survey participants using this Facebook app. 

| Dataset statistics |  |
| --- | ----------- |
| Nodes |	4039 |
| Edges |	88234 |
| Average clustering coefficient |	0.6055 |
| Number of triangles |	1612010 |
| Fraction of closed triangles |	0.2647 |
| Diameter (longest shortest path) |	8 |
| 90-percentile effective diameter |	4.7 |

## notebook details
- implementation and analysis of SIR model with Trust Mechanism <cite>[2]</cite>- [Trust_in_SIR.ipynb](https://github.com/shivani-nandani/rumor-spread/blob/main/Trust_in_SIR.ipynb)
- implementation and analysis of SIHR model <cite>[3]</cite> - [SIHR.ipynb](https://github.com/shivani-nandani/rumor-spread/blob/main/SIHR.ipynb)
- implementation and analysis of SICR model <cite>[4]</cite> - [SICR.ipynb](https://github.com/shivani-nandani/rumor-spread/blob/main/SICR.ipynb)
- implementation of SICHR model with Trust Mechanism - [SIHCR_Trust.ipynb](https://github.com/shivani-nandani/rumor-spread/blob/main/SIHCR_Trust.ipynb)
- analysis of models on Facebook Social Circles network <cite>[5]</cite> - [facebook_network_analysis.ipynb](https://github.com/shivani-nandani/rumor-spread/blob/main/facebook_network_analysis.ipynb)
- block diagram of SIHCR model with Trust Mechanism - [SIHCR_trust_block_dia.png](https://github.com/shivani-nandani/rumor-spread/blob/main/SIHCR_trust_block_dia.png)

## references 
[1] M. Nekovee, Y. Moreno, G. Bianconi, and M. Marsili. Theory of rumour spreading in complex social networks. Physica A: Statistical Mechanics and its Applications,374(1):457–470, 2007

[2] Ya-Qi Wang, Xiao-Yuan Yang, Yi-Liang Han, and Xu-An Wang. Rumor spreading model with trust mechanism in complex social networks. Communications in Theoretical Physics, 59(4):510–516, apr 2013.

[3] Laijun Zhao, Jiajia Wang, Yucheng Chen, Qin Wang, Jingjing Cheng, and Hongxin Cui. SIHR rumor spreading model in social networks. Physica A: Statistical Mechanics and its Applications, 391(7):2444–2453, 2012.

[4] Yongli Zan, Jianliang Wu, Ping Li, and Qinglin Yu. SICR rumor spreading modeling complex networks: Counterattack and self-resistance. Physica A: Statistical Mechanics and its Applications, 405:159–170, 2014.

[5] Jure Leskovec, et al. "SNAP Datasets: Stanford Large Network Dataset Collection." http://snap.stanford.edu/data. (2014).
