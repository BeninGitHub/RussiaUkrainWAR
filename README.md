# Russia Ukraine Crisis


Download link for the dataset is [here](https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows).

### Motivation
Online social networks such as Twitter play an important role in how people stay informed and exchange reactions. In particular, online social networks during crisis events embody a key opportunity for studying the portability of computational models for various tasks (e.g., information extraction, complex event understanding, misinformation detection, etc.), due to differences in domain, entities, and event types. Wepresent the **Russia-Ukraine Crisis dataset**, with over 500K public user posts and comments in our first release.

![image](https://user-images.githubusercontent.com/81369617/167262526-d84739fa-7803-4557-bb6d-fec00cd45f88.png)
### Dataset Details
We initiated our data collection process when the crisis escalated with Russia's special military operation on April first till April 10th, that because we were trying to bring a specific data regarding what happened in Kyiev, the capital city of Ukrain. in that time Russia almost took over the capital of Ukraine and we could have seen that the comments all over the internet changing from side to side. The following information are included in the *Russia-Ukraine Crisis* dataset:
|      |  |
| ----------- | ----------- |
| user information     | username, location, following, followers, \# of followers     |
| post content  | the main text      |
| post metadata  | the \# of likes \& shares on the post, and the publication timestamp of the post    |
| post comments | information similar to the previous three rows, for all comments underneath a user post      |

We are continuing the data collection process to follow the latest development of events in the ongoing crisis, and will update our dataset daily. At present, our dataset statistics is summarized as below:
| (prior to one-hop expansion) |  |
| ----------- | ----------- |
| # Unique Posts w/ Relevant Keywords | 130 K |
| # Users for these Unique Posts  | 200 |
| # Corresponding Comments in Total | 3.4 M |
| # Users Altogether, w/ Comments Included | 122 K    
| | |
| Avg # Like/Reacts per Posts | 4338 |
| Avg # Shares per Post | 163 |
| | |

Keywords: *俄罗斯 (Russia), 乌克兰 (Ukraine), 普京 (Putin), 泽连斯基 (Zelenskyy), 基辅 (Kiev), 北约 (Nato), 车臣 (Chechen), 俄乌 (Russia-Ukraine), 俄方 (Russian side), 乌方 (Ukraine side), 俄军 (Russia army), 乌军 (Ukraine army), 哈尔科夫 (Kharkiv), 敖德萨 (Odesa), 切尔诺贝 (Chernobyl)*

### Use Cases
There are many interesting task settings that can be experimented with, using our Russo-Ukranian Crises Weibo dataset. These include event clustering, false rumor detection, portability of news analytic methodologies across Twitter and Weibo domains, amongst many more. 

**Data Usage Guidelines:** We declare the ownership of the source data to the corresponding media source and social media users who created this kind of public User Generated Content (UGC), and we only collect, organize and filter them. 如有这方面的问题反馈，请像作者沟通（定会重视修正）～ 谢谢。

### Related Work
A team at HKUST has released a [Russo-Ukranian Crises Twitter dataset](https://github.com/ehsanulhaq1/russo_ukraine_dataset). It is generally interesting to uncover patterns universal across platforms, regulated by a separate set of rules and participated by a separate set of users with different user behavior. Note that Twitter data (multilingual) involves English as the primary language, while Weibo data involves Chinese as the primary language.

## References
If you use our dataset or find our work helpful, please cite:
```
@article{fung2022weibo,
  title={A Weibo Dataset for the 2022 Russo-Ukrainian Crisis},
  author={Fung, Yi R and Ji, Heng},
  journal={arXiv preprint arXiv:2203.05967},
  year={2022}
}
```
Author contact information: yifung2@illinois.edu
