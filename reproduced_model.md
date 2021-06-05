## Reproduced Model List

| Task                                | Traditional     | CNN-based                           | RNN-based                                                    | GCN-based                                                    | Attention-based                                              |
| ----------------------------------- | --------------- | ----------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Traffic flow prediction             | AutoEncoder [1] | ST-ResNet [2],   ACFM [3], STDN [4] | FC-RNN [5],   Seq2Seq [6]                                    | AGCRN [7],   CONVGCN [8], STSGCN [9], ToGCN [10], Multi-STGCnet [11] | ASTGCN [12],   ResLSTM [13], CRANN [14], DGCN [15], DSAN [16] |
| Traffic speed prediction            | AutoEncoder [1] | —                                   | FC-RNN [5],   Seq2Seq [6]                                    | DCRNN [17],   STGCN [18], GWNET [19], MTGNN [20], TGCN [21], TGCLSTM [22], ATDM [23], GTS [24] | GMAN [25],   STAGGCN [26], HGCN [27], ST-MGAT [28]           |
| On-Demand service prediction        | AutoEncoder [1] | DMVSTNet [29]                       | FC-RNN [5],   Seq2Seq [6]                                    | CCRNN [30]                                                   | STG2Seq [31]                                                 |
| Trajectory next-location prediction | FPMC [32]       | —                                   | RNN [33],   ST-RNN [34], ATST-LSTM [35], SERM [36], DeepMove [37], HST-LSTM [38], LSTPM [39], CARA [40] | —                                                            | GeoSAN [41],   STAN [42]                                     |

#### Citation list

[1] This baseline model is implemented by ourselves for traffic state prediction task based on AutoEncoder.

[2] Junbo Zhang, Yu Zheng, and Dekang Qi. 2017. Deep Spatio-Temporal Residual Networks for Citywide Crowd Flows Prediction. In AAAI. AAAI Press, 1655–1661.

[3] Lingbo Liu, Ruimao Zhang, Jiefeng Peng, Guanbin Li, Bowen Du, and Liang Lin. 2018. Attentive Crowd Flow Machines. In ACM Multimedia. ACM, 1553–1561.

[4] Huaxiu Yao, Xianfeng Tang, Hua Wei, Guanjie Zheng, and Zhenhui Li. 2019. Revisiting Spatial-Temporal Similarity: A Deep Learning Framework for Traffic Prediction. In AAAI. AAAI Press, 5668–5675.

[5] This baseline model is implemented by ourselves for traffic state prediction task based on RNN.

[6] This baseline model is implemented by ourselves for traffic state prediction task based on Encoder-Decoder structure.

[7] Lei Bai, Lina Yao, Can Li, Xianzhi Wang, and Can Wang. 2020. Adaptive Graph Convolutional Recurrent Network for Traffic Forecasting. In NeurIPS.

[8] Jinlei Zhang, Feng Chen, Yinan Guo, and Xiaohong Li. 2020. Multi-graph convolutional network for short-term passenger flow forecasting in urban rail transit. IET Intell. Transp. Syst.14, 10 (2020), 1210–1217.

[9] Chao Song, Youfang Lin, Shengnan Guo, and Huaiyu Wan. 2020. Spatial-Temporal Synchronous Graph Convolutional Networks: A New Framework for Spatial-Temporal Network Data Forecasting. In AAAI. AAAI Press, 914–921.

[10] Han Qiu, Qinkai Zheng, Mounira Msahli, Gerard Memmi, Meikang Qiu, and Jialiang Lu. 2020. Topological Graph Convolutional Network-Based Urban Traffic Flow and Density Prediction. IEEE Trans. Intell. Transp. Syst.(2020).

[11] Jiexia Ye, Juanjuan Zhao, Kejiang Ye, and Chengzhong Xu. 2020. Multi-STGCnet:A Graph Convolution Based Spatial-Temporal Framework for Subway Passenger Flow Forecasting. In IJCNN. IEEE, 1–8.

[12] Shengnan Guo, Youfang Lin, Ning Feng, Chao Song, and Huaiyu Wan. 2019.Attention Based Spatial-Temporal Graph Convolutional Networks for Traffic Flow Forecasting. In AAAI. AAAI Press, 922–929.

[13] Jinlei Zhang, Feng Chen, Zhiyong Cui, Yinan Guo, and Yadi Zhu. 2020.  Deep learning architecture for short-term passenger flow forecasting in urban rail transit. IEEE Trans. Intell. Transp. Syst.(2020).

[14] Rodrigo  de  Medrano  and  José  Luis  Aznarte.  2020. A  Spatio-Temporal  Spot-Forecasting Framework for Urban Traffic Prediction. CoRR abs/2003.13977 (2020).

[15] Kan Guo, Yongli Hu, Zhen Qian, Yanfeng Sun, Junbin Gao, and Baocai Yin. 2020. Dynamic Graph Convolution Network for Traffic Forecasting Based on Latent Network of Laplace Matrix Estimation. IEEE Trans. Intell. Transp. Syst.(2020).

[16] Haoxing Lin, Rufan Bai, Weijia Jia, Xinyu Yang, and Yongjian You. 2020. Preserving Dynamic Attention for Long-Term Spatial-Temporal Prediction. In KDD. ACM, 36–46.

[17] Yaguang Li, Rose Yu, Cyrus Shahabi, and Yan Liu. 2018. Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting. In ICLR (Poster). OpenReview.net.

[18] Bing Yu, Haoteng Yin, and Zhanxing Zhu. 2018. Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting. In IJCAI. ijcai.org, 3634–3640.

[19] Zonghan Wu, Shirui Pan, Guodong Long, Jing Jiang, and Chengqi Zhang. 2019. Graph Wave Net for Deep Spatial-Temporal Graph Modeling. In IJCAI. ijcai.org, 1907–1913.

[20] Zonghan Wu, Shirui Pan, Guodong Long, Jing Jiang, Xiaojun Chang, and Chengqi Zhang. 2020.  Connecting the Dots: Multivariate Time Series Forecasting with Graph Neural Networks. In KDD. ACM, 753–763.

[21] Ling Zhao, Yujiao Song, Chao Zhang, Yu Liu, Pu Wang, Tao Lin, Min Deng, and Haifeng Li. 2020. T-GCN: A Temporal Graph Convolutional Network for Traffic Prediction. IEEE Trans. Intell. Transp. Syst. 21, 9 (2020), 3848–385.

[22] Zhiyong Cui, Kristian Henrickson, Ruimin Ke, and Yinhai Wang. 2020.  Traffic Graph Convolutional Recurrent Neural Network: A Deep Learning Frame work for Network-Scale Traffic Learning and Forecasting. IEEE Trans. Intell. Transp. Syst. 21, 11 (2020), 4883–4894.

[23] Rodrigo de Medrano and José Luis Aznarte. 2020.  On the Inclusion of Spatial Information for Spatio-Temporal Neural Networks. CoRR abs/2007.07559 (2020).

[24] Chao Shang, Jie Chen, and Jinbo Bi. 2021. Discrete Graph Structure Learning for Forecasting Multiple Time Series. CoRR abs/2101.06861 (2021).

[25] Chuanpan Zheng, Xiaoliang Fan, Cheng Wang, and Jianzhong Qi. 2020. GMAN: A Graph Multi-Attention Network for Traffic Prediction. In AAAI. AAAI Press,1234–1241.

[26] Bin Lu, Xiaoying Gan, Haiming Jin, Luoyi Fu, and Haisong Zhang. 2020.  Spatiotemporal Adaptive Gated Graph Convolution Network for Urban Traffic Flow Forecasting. In CIKM. ACM, 1025–1034.

[27] Kan Guo, Yongli Hu, Yanfeng Sun, Sean Qian, Junbin Gao, and Baocai Yin. 2021. Hierarchical Graph Convolution Networks for Traffic Forecasting. In AAAI. AAAI Press,151-159.

[28] Kelang Tian, Jingjie Guo, Kejiang Ye, and Cheng-Zhong Xu. 2020.  ST-MGAT: Spatial-Temporal Multi-Head Graph Attention Networks for Traffic Forecasting. In ICTAI. IEEE, 714–721.

[29] Huaxiu Yao, Fei Wu, Jintao Ke, Xianfeng Tang, Yitian Jia, Siyu Lu, Pinghua Gong, Jieping Ye, and Zhenhui Li. 2018. Deep Multi-View Spatial-Temporal Network for Taxi Demand Prediction. In AAAI. AAAI Press, 2588.

[30] Junchen Ye, Leilei Sun, Bowen Du, Yanjie Fu, and Hui Xiong. 2021.  Coupled Layer-wise Graph Convolution for Transportation Demand Prediction. In AAAI. AAAI Press, 4617–46.

[31] Lei Bai, Lina Yao, Salil S. Kanhere, Xianzhi Wang, and Quan Z. Sheng. 2019. STG2Seq: Spatial-Temporal Graph to Sequence Model for Multi-step Passenger Demand Forecasting. In IJCAI. ijcai.org, 1981-1987.

[32] Steffen Rendle, Christoph Freudenthaler, and Lars Schmidt-Thieme. 2010. Factorizing personalized Markov chains for next-basket recommendation. In WWW. ACM, 811–820.

[33] This baseline model is implemented by ourselves for trajectory next-location prediction task based on RNN.

[34] Qiang Liu, Shu Wu, Liang Wang, and Tieniu Tan. 2016. Predicting the Next Location: A Recurrent Model with Spatial and Temporal Contexts. In AAAI. AAAI Press, 194–200.

[35] Liwei Huang, Yutao Ma, Shibo Wang, and Yanbo Liu. 2019. An attention-based spatiotemporal lstm network for next poi recommendation. IEEE Transactions on Services Computing(2019).

[36] Di Yao, Chao Zhang, Jian-Hui Huang, and Jingping Bi. 2017. SERM: A Recurrent Model for Next Location Prediction in Semantic Trajectories. In CIKM. ACM, 2411–24.

[37] Jie Feng, Yong Li, Chao Zhang, Funing Sun, Fanchao Meng, Ang Guo, and Depeng Jin. 2018. DeepMove: Predicting Human Mobility with Attentional Recurrent Networks. In WWW. ACM, 1459–1468.

[38] Dejiang Kong and Fei Wu. 2018.  HST-LSTM: A Hierarchical Spatial-Temporal Long-Short Term Memory Network for Location Prediction. In IJCAI. ijcai.org, 2341–2347.

[39] Ke Sun, Tieyun Qian, Tong Chen, Yile Liang, Quoc Viet Hung Nguyen, and HongzhiYin. 2020. Where to Go Next: Modeling Long- and Short-Term User Preferences for Point-of-Interest Recommendation. In AAAI. AAAI Press, 214-221.

[40] Jarana Manotumruksa, Craig Macdonald, and Iadh Ounis. 2018.  A Contextual Attention Recurrent Architecture for Context-Aware Venue Recommendation. In SIGIR. ACM, 555–564.

[41] Defu Lian, Yongji Wu, Yong Ge, Xing Xie, and Enhong Chen. 2020. Geography-Aware Sequential Location Recommendation. In KDD. ACM, 2009–2019.

[42] Yingtao Luo, Qiang Liu, and Zhaocheng Liu. 2021. STAN: Spatio-Temporal Attention Network for Next Location Recommendation. CoRR abs/2102.04095 (2021).

