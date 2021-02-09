# awesome-offline-rl
This is a collection of research and review papers for **offline reinforcement learning (offline rl)**. Feel free to star and fork.


Maintainers:
- Haruka Kiyohara (Tokyo Institute of Technology)
- [Yuta Saito](http://usaito.github.io/) (Hanjuku-kaso Co., Ltd.)

We are looking for more contributors and maintainers! Please feel free to [pull requests](https://github.com/usaito/awesome-offline-rl/pulls).

```
format: [title](paper link) by authors, arXiv/conferences/jornals/, year. [links]
```

For any question, feel free to contact: saito@hanjuku-kaso.com


## Papers

### Review Papers

- [Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems](https://arxiv.org/abs/2005.01643) by Sergey Levine, Aviral Kumar, George Tucker, and Justin Fu, arXiv2020.

### Offline RL: Theory/Methods
- [Finite Sample Analysis of Minimax Offline Reinforcement Learning: Completeness, Fast Rates and First-Order Efficiency](https://arxiv.org/abs/2102.02981) by Masatoshi Uehara, Masaaki Imaizumi, Nan Jiang, Nathan Kallus, Wen Sun and Tengyang Xie, arXiv2021.
- [Fast Rates for the Regret of Offline Reinforcement Learning](https://arxiv.org/abs/2102.00479) by Yichun Hu, Nathan Kallus and Masatoshi Uehara, arXiv2021.
- [Near-Optimal Offline Reinforcement Learning via Double Variance Reduction](https://arxiv.org/abs/2102.01748) by Ming Yin, Yu Bai and Yu-Xiang Wang, arXiv2021.
- [Batch Reinforcement Learning Through Continuation Method](https://openreview.net/forum?id=po-DLlBuAuz) by Yijie Guo, Shengyu Feng, Nicolas Le Roux, Ed Chi, Honglak Lee and Minmin Chen, ICLR2021.
- [Model-Based Visual Planning with Self-Supervised Functional Distances](https://openreview.net/forum?id=UcoXdfrORC) by Stephen Tian, Suraj Nair, Frederik Ebert, Sudeep Dasari, Benjamin Eysenbach, Chelsea Finn and Sergey Levine, ICLR2021.
- [Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://openreview.net/forum?id=3hGNqpI4WS) by Tatsuya Matsushima, Hiroki Furuta, Yutaka Matsuo, Ofir Nachum and Shixiang Gu, ICLR2021.
- [Efficient Evaluation of Natural Stochastic Policies in Offline Reinforcement Learning](https://arxiv.org/abs/2006.03886) by Nathan Kallus and Masatoshi Uehara, arXiv2020. [[code](https://github.com/CausalML/NaturalStochasticOPE)]
- [Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359) by Ashvin Nair, Murtaza Dalal, Abhishek Gupta and Sergey Levine, arXiv2020. [[website](https://awacrl.github.io/)]
- [DisCor: Corrective Feedback in Reinforcement Learning via Distribution Correction](https://arxiv.org/abs/2003.07305) by Aviral Kumar, Abhishek Gupta and Sergey Levine, arXiv2020.
- [Doubly Robust Off-Policy Value and Gradient Estimation for Deterministic Policies](https://papers.nips.cc/paper/2020/hash/75df63609809c7a2052fdffe5c00a84e-Abstract.html) by Nathan Kallus and Masatoshi Uehara, NeurIPS2020.
- [Critic Regularized Regression](https://proceedings.neurips.cc/paper/2020/hash/588cb956d6bbe67078f29f8de420a13d-Abstract.html) by Ziyu Wang, Alexander Novikov, Konrad Zolna, Josh S. Merel, Jost Tobias Springenberg, Scott E. Reed, Bobak Shahriari, Noah Siegel, Caglar Gulcehre, Nicolas Heess and Nando de Freitas, NeurIPS2020
- [Provably Good Batch Off-Policy Reinforcement Learning Without Great Exploration](https://papers.nips.cc/paper/2020/hash/0dc23b6a0e4abc39904388dd3ffadcd1-Abstract.html) by Yao Liu, Adith Swaminathan, Alekh Agarwal and Emma Brunskill, NeurIPS2020.
- [Conservative Q-Learning for Offline Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/0d2b2061826a5df3221116a5085a6052-Abstract.html) by Aviral Kumar, Aurick Zhou, George Tucker, and Sergey Levine, NeurIPS2020. [[website](https://sites.google.com/view/cql-offline-rl)] [[code](https://github.com/aviralkumar2907/CQL)]
- [BAIL: Best-Action Imitation Learning for Batch Deep Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/d55cbf210f175f4a37916eafe6c04f0d-Abstract.html) by Xinyue Chen, Zijian Zhou, Zheng Wang, Che Wang, Yanqiu Wu and Keith Ross, NeurIPS2020.
- [MOPO: Model-based Offline Policy Optimization](https://papers.nips.cc/paper/2020/hash/a322852ce0df73e204b7e67cbbef0d0a-Abstract.html) by Tianhe Yu, Garrett Thomas, Lantao Yu, Stefano Ermon, James Y. Zou, Sergey Levine, Chelsea Finn and Tengyu Ma, NeurIPS2020. [[code](https://github.com/tianheyu927/mopo)]
- [MOReL : Model-Based Offline Reinforcement Learning](https://papers.nips.cc/paper/2020/hash/f7efa4f864ae9b88d43527f4b14f750f-Abstract.html) by Rahul Kidambi, Aravind Rajeswaran, Praneeth Netrapalli and Thorsten Joachims, NeurIPS2020.
- [Keep Doing What Worked: Behavior Modelling Priors for Offline Reinforcement Learning](https://openreview.net/forum?id=rke7geHtwH) by Noah Siegel, Jost Tobias Springenberg, Felix Berkenkamp, Abbas Abdolmaleki, Michael Neunert, Thomas Lampe, Roland Hafner, Nicolas Heess and Martin Riedmiller, ICLR2020.
- [Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://papers.nips.cc/paper/2019/hash/c2073ffa77b5357a498057413bb09d3a-Abstract.html) by Aviral Kumar, Justin Fu, George Tucker,  and Sergey Levine, NeurIPS2019. [[website](https://sites.google.com/view/bear-off-policyrl)] [[code](https://github.com/aviralkumar2907/BEAR)]
- [Way Off-Policy Batch Deep Reinforcement Learning of Implicit Human Preferences in Dialog](https://arxiv.org/abs/1907.00456) by Natasha Jaques, Asma Ghandeharioun, Judy Hanwen Shen, Craig Ferguson, Agata Lapedriza, Noah Jones, Shixiang Gu and Rosalind Picard, arXiv2019.
- [Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/abs/1911.11361) by Yifan Wu, George Tucker and Ofir Nachum, arXiv2019.
- [Off-Policy Deep Reinforcement Learning without Exploration](http://proceedings.mlr.press/v97/fujimoto19a.html) by Scott Fujimoto, David Meger and Doina Precup, ICML2019.
- [Safe Policy Improvement with Baseline Bootstrapping](http://proceedings.mlr.press/v97/laroche19a.html) by Romain Laroche, Paul Trichelair and Remi Tachet Des Combes, ICML2019.
- [Deep Exploration via Bootstrapped DQN](https://papers.nips.cc/paper/2016/hash/8d8818c8e140c64c743113f563cf750f-Abstract.html) by Ian Osband, Charles Blundell, Alexander Pritzel and Benjamin Van Roy, NeurIPS2016.
- [Guided Policy Search](http://proceedings.mlr.press/v28/levine13.html) by Sergey Levine and Vladlen Koltun, ICML2013.

### Offline RL: Benchmarks/Experiments/Applications
- [Near Real-World Benchmarks for Offline Reinforcement Learning](https://arxiv.org/abs/2102.00714) by Rongjun Qin, Songyi Gao, Xingyuan Zhang, Zhen Xu, Shengkai Huang, Zewen Li, Weinan Zhang and Yang Yu, arXiv2021. [[website](http://polixir.ai/research/neorl)]
- [Offline Reinforcement Learning Hands-On](https://arxiv.org/abs/2011.14379) by Louis Monier, Jakub Kmec, Alexandre Laterre, Thomas Pierrot, Valentin Courgeau, Olivier Sigaud, Karim Beguir, arXiv2020.
- [D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://arxiv.org/abs/2004.07219) by Justin Fu, Aviral Kumar, Ofir Nachum, George Tucker and Sergey Levine, arXiv2020. [[code](https://github.com/rail-berkeley/d4rl)]
- [RL Unplugged: Benchmarks for Offline Reinforcement Learning](https://arxiv.org/abs/2006.13888) by Caglar Gulcehre, Ziyu Wang, Alexander Novikov, Tom Le Paine, Sergio Gomez Colmenarejo, Konrad Zolna, Rishabh Agarwal, Josh Merel, Daniel Mankowitz, Cosmin Paduraru, Gabriel Dulac-Arnold, Jerry Li, Mohammad Norouzi, Matt Hoffman, Ofir Nachum, George Tucker, Nicolas Heess and Nando de Freitas, arXiv2020. [[code](https://github.com/deepmind/deepmind-research/tree/master/rl_unplugged)]
- [An Optimistic Perspective on Offline Reinforcement Learning](http://proceedings.mlr.press/v119/agarwal20c.html) by Rishabh Agarwal, Dale Schuurmans, and Mohammad Norouzi, ICML2020. [[website](https://offline-rl.github.io/)]
- [Off-policy Learning in Two-stage Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3366423.3380130) by Jiaqi Ma, Zhe Zhao, Xinyang Yi, Ji Yang, Minmin Chen, Jiaxi Tang, Lichan Hong and Ed H Chi, WWW2020.
- [Benchmarking Batch Deep Reinforcement Learning Algorithms](https://arxiv.org/abs/1910.01708) by Scott Fujimoto, Edoardo Conti, Mohammad Ghavamzadeh and Joelle Pineau, arXiv2019.
- [Top-K Off-Policy Correction for a REINFORCE Recommender System](https://arxiv.org/abs/1812.02353) by Minmin Chen, Alex Beutel, Paul Covington, Sagar Jain, Francois Belletti, and Ed Chi, WSDM2019.

### Off-Policy Evaluation: Theory/Methods
#### Contextual Bandits

- [Off-Policy Evaluation of Slate Policies under Bayes Risk](https://arxiv.org/abs/2101.02553) by Nikos Vlassis, Fernando Amat Gil, and Ashok Chandrashekar, arXiv2021.
- [Bandit Overfitting in Offline Policy Learning](https://arxiv.org/abs/2006.15368) by David Brandfonbrener, William F. Whitney, Rajesh Ranganath, and Joan Bruna, arXiv2020.
- [Optimal Off-Policy Evaluation from Multiple Logging Policies](https://arxiv.org/abs/2010.11002) by Nathan Kallus, Yuta Saito, and Masatoshi Uehara, arXiv2020. [[code](https://github.com/CausalML/MultipleLoggers)]
- [A Practical Guide of Off-Policy Evaluation for Bandit Problems](https://arxiv.org/abs/2010.12470) by Masahiro Kato, Kenshi Abe, Kaito Ariu, and Shota Yasui, arXiv2020.
- [Off-Policy Evaluation and Learning for External Validity under a Covariate Shift](https://papers.nips.cc/paper/2020/hash/0084ae4bc24c0795d1e6a4f58444d39b-Abstract.html) by Masatoshi Uehara, Masahiro Kato, and Shota Yasui, NeurIPS2020.
- [Counterfactual Evaluation of Slate Recommendations with Sequential Reward Interactions](https://arxiv.org/abs/2007.12986) by James McInerney, Brian Brost, Praveen Chandar, Rishabh Mehrotra, and Ben Carterette, KDD2020.
- [Off-policy Bandits with Deficient Support](https://dl.acm.org/doi/abs/10.1145/3394486.3403139) by Noveen Sachdeva, Yi Su, and Thorsten Joachims, KDD2020.
- [Doubly robust off-policy evaluation with shrinkage](http://proceedings.mlr.press/v119/su20a.html) by Yi Su, Maria Dimakopoulou, Akshay Krishnamurthy, and Miroslav Dudik, ICML2020.
- [Adaptive Estimator Selection for Off-Policy Evaluation](http://proceedings.mlr.press/v119/su20d.html) by Yi Su, Pavithra Srinath, and Akshay Krishnamurthy, ICML2020.
- [Off-policy Bandit and Reinforcement Learning](https://arxiv.org/abs/2002.08536) by Yusuke Narita, Shota Yasui, and Kohei Yata, arXiv2020.
- [Distributionally Robust Policy Evaluation and Learning in Offline Contextual Bandits](http://proceedings.mlr.press/v119/si20a.html) by Nian Si, Fan Zhang, Zhengyuan Zhou, and Jose Blanchet, ICML2020.
- [Efficient Policy Learning from Surrogate-Loss Classification Reductions](http://proceedings.mlr.press/v119/bennett20a.html) by Andrew Bennett and Nathan Kallus, ICML2020. [[code](https://github.com/CausalML/ESPRM)]
- [More Efficient Policy Learning via Optimal Retargeting](https://www.tandfonline.com/doi/abs/10.1080/01621459.2020.1788948?journalCode=uasa20) by Nathan Kallus, JASA2020.
- [Semi-Parametric Efficient Policy Learning with Continuous Actions](https://papers.nips.cc/paper/2019/hash/08b7dc6e8b36bcaac15847827b7951a9-Abstract.html) by Victor Chernozhukov, Mert Demirer, Greg Lewis, and Vasilis Syrgkanis, NeurIPS2019.
- [Balanced Off-Policy Evaluation in General Action Spaces](http://proceedings.mlr.press/v108/sondhi20a.html) by Arjun Sondhi, David Arbour, and Drew Dimmery, AISTATS2019.
- [Policy Evaluation with Latent Confounders via Optimal Balance](https://papers.nips.cc/paper/2019/hash/7c4bf50b715509a963ce81b168ca674b-Abstract.html) by Andrew Bennett and Nathan Kallus, NeuIPS2019.
- [Focused Context Balancing for Robust Offline Policy Evaluation](https://dl.acm.org/doi/10.1145/3292500.3330852) by Hao Zou, Kun Kuang, Boqi Chen, Peixuan Chen, and Peng Cui, KDD2019.
- [On the Design of Estimators for Bandit Off-Policy Evaluation](http://proceedings.mlr.press/v97/vlassis19a.html) by Nikos Vlassis, Aurelien Bibaut, Maria Dimakopoulou, and Tony Jebara, ICML2019.
- [CAB: Continuous Adaptive Blending for Policy Evaluation and Learning](http://proceedings.mlr.press/v97/su19a.html) by Yi Su, Lequn Wang, Michele Santacatterina, and Thorsten Joachims, ICML2019.
- [Efficient Counterfactual Learning from Bandit Feedback](https://arxiv.org/abs/1809.03084) by Yusuke Narita, Shota Yasui, and Kohei Yata, AAAI2019.
- [Policy Evaluation and Optimization with Continuous Treatments](http://proceedings.mlr.press/v84/kallus18a.html) by Nathan Kallus and Angela Zhou, AISTATS2019.
- [Offline Evaluation of Ranking Policies with Click Models](https://dl.acm.org/doi/10.1145/3219819.3220028) by Shuai Li, Yasin Abbasi-Yadkori, Branislav Kveton, S. Muthukrishnan, Vishwa Vinay, and Zheng Wen, KDD2018.
- [Effective Evaluation using Logged Bandit Feedback from Multiple Loggers](https://arxiv.org/abs/1703.06180) by Aman Agarwal, Soumya Basu, Tobias Schnabel, and Thorsten Joachims, KDD2018.
- [Deep Learning with Logged Bandit Feedback](https://openreview.net/forum?id=SJaP_-xAb) by Thorsten Joachims, Adith Swaminathan, and Maarten de Rijke, ICLR2018.
- [Off-policy Evaluation for Slate Recommendation](https://papers.nips.cc/paper/2017/hash/5352696a9ca3397beb79f116f3a33991-Abstract.html) by Adith Swaminathan, Akshay Krishnamurthy, Alekh Agarwal, Miroslav Dudík, John Langford, Damien Jose, and Imed Zitouni, NeurIPS2017.
- [Optimal and Adaptive Off-policy Evaluation in Contextual Bandits](https://arxiv.org/abs/1612.01205) by Yu-Xiang Wang, Alekh Agarwal, and Miroslav Dudik, ICML2017.
- [Data-Efficient Policy Evaluation Through Behavior Policy Search](http://proceedings.mlr.press/v70/hanna17a.html) by Josiah P. Hanna, Philip S. Thomas, Peter Stone and Scott Niekum, ICML2017.
- [The Self-Normalized Estimator for Counterfactual Learning](https://papers.nips.cc/paper/2015/hash/39027dfad5138c9ca0c474d71db915c3-Abstract.html) by Adith Swaminathan and Thorsten Joachims, NeurIPS2015.
-  [Doubly Robust Policy Evaluation and Optimization](https://arxiv.org/abs/1503.02834) by Miroslav Dudík, Dumitru Erhan, John Langford, and Lihong Li, ICML2011.
- [Unbiased Offline Evaluation of Contextual-bandit-based News Article Recommendation Algorithms](https://dl.acm.org/doi/10.1145/1935826.1935878) by Lihong Li, Wei Chu, John Langford, and Xuanhui Wang, WSDM2011.
#### Reinforcement Learning
- [Bootstrapping Statistical Inference for Off-Policy Evaluation](https://arxiv.org/abs/2102.03607) by Botao Hao, Xiang (Jack)Ji, Yaqi Duan, Hao Lu, Csaba Szepesvári and Mengdi Wang, arXiv2021.
- [Average-Reward Off-Policy Policy Evaluation with Function Approximation](https://arxiv.org/abs/2101.02808) by Shangtong Zhang, Yi Wan, Richard S. Sutton, and Shimon Whiteson, arXiv2021.
- [Optimal Mixture Weights for Off-Policy Evaluation with Multiple Behavior Policies](https://arxiv.org/abs/2011.14359) by Jinlin Lai, Lixin Zou, and Jiaxing Song, arXiv2020.
- [Kernel Methods for Policy Evaluation: Treatment Effects, Mediation Analysis, and Off-Policy Planning](https://arxiv.org/abs/2010.04855) by Rahul Singh, Liyuan Xu, and Arthur Gretton, arXiv2020.
- [Off-policy Policy Evaluation For Sequential Decisions Under Unobserved Confounding](https://papers.nips.cc/paper/2020/hash/da21bae82c02d1e2b8168d57cd3fbab7-Abstract.html) by Hongseok Namkoong, Ramtin Keramati, Steve Yadlowsky, and Emma Brunskill, NeurIPS2020.
- [CoinDICE: Off-Policy Confidence Interval Estimation](https://papers.nips.cc/paper/2020/hash/6aaba9a124857622930ca4e50f5afed2-Abstract.html) by Bo Dai, Ofir Nachum, Yinlam Chow, Lihong Li, Csaba Szepesvari, and Dale Schuurmans, NeurIPS2020.
- [Off-Policy Interval Estimation with Lipschitz Value Iteration](https://papers.nips.cc/paper/2020/hash/59accb9fe696ce55e28b7d23a009e2d1-Abstract.html) by Ziyang Tang, Yihao Feng, Na Zhang, Jian Peng, and Qiang Liu, NeurIPS2020.
- [Off-Policy Evaluation via the Regularized Lagrangian](https://papers.nips.cc/paper/2020/hash/488e4104520c6aab692863cc1dba45af-Abstract.html) by Mengjiao Yang, Ofir Nachum, Bo Dai, Lihong Li, and Dale Schuurmans, NeurIPS2020.
- [Minimax Value Interval for Off-Policy Evaluation and Policy Optimization](https://papers.nips.cc/paper/2020/hash/1cd138d0499a68f4bb72bee04bbec2d7-Abstract.html) by Nan Jiang and Jiawei Huang, NeurIPS2020.
- [Statistical Bootstrapping for Uncertainty Estimation in Off-Policy Evaluation](https://arxiv.org/abs/2007.13609) by Ilya Kostrikov and Ofir Nachum, arXiv2020.
- [Off-policy Evaluation in Infinite-Horizon Reinforcement Learning with Latent Confounders](https://arxiv.org/abs/2007.13893) by Andrew Bennett, Nathan Kallus, Lihong Li, and Ali Mousavi, arXiv2020.
- [Confident Off-Policy Evaluation and Selection through Self-Normalized Importance Weighting](https://arxiv.org/abs/2006.10460) by Ilja Kuzborskij, Claire Vernade, András György, and Csaba Szepesvári, arXiv2020.
- [Infinite-horizon Off-Policy Policy Evaluation with Multiple Behavior Policies](https://iclr.cc/virtual_2020/poster_rkgU1gHtvr.html) by Xinyun Chen, Lu Wang, Yizhe Hang, Heng Ge, and Hongyuan Zha, ICLR2020.
- [Doubly Robust Bias Reduction in Infinite Horizon Off-Policy Estimation](https://iclr.cc/virtual_2020/poster_S1glGANtDr.html) by Ziyang Tang, Yihao Feng, Lihong Li, Dengyong Zhou, and Qiang Liu, ICLR2020.
- [Black-box Off-policy Estimation for Infinite-Horizon Reinforcement Learning](https://iclr.cc/virtual_2020/poster_S1ltg1rFDS.html) by Ali Mousavi, Lihong Li, Qiang Liu, and Denny Zhou, ICLR2020.
- [Minimax-Optimal Off-Policy Evaluation with Linear Function Approximation](http://proceedings.mlr.press/v119/duan20b.html) by Yaqi Duan, Zeyu Jia, and Mengdi Wang, ICML2020.
- [Interpretable Off-Policy Evaluation in Reinforcement Learning by Highlighting Influential Transitions](http://proceedings.mlr.press/v119/gottesman20a.html) by Omer Gottesman, Joseph Futoma, Yao Liu, Sonali Parbhoo, Leo Celi, Emma Brunskill, and Finale Doshi-Velez, ICML2020.
- [Double Reinforcement Learning for Efficient and Robust Off-Policy Evaluation](http://proceedings.mlr.press/v119/kallus20b.html) by Nathan Kallus and Masatoshi Uehara, ICML2020.
- [Understanding the Curse of Horizon in Off-Policy Evaluation via Conditional Importance Sampling](http://proceedings.mlr.press/v119/liu20a.html) by Yao Liu, Pierre-Luc Bacon, and Emma Brunskill, ICML2020.
- [Minimax Weight and Q-Function Learning for Off-Policy Evaluation](http://proceedings.mlr.press/v119/uehara20a.html) by Masatoshi Uehara, Jiawei Huang, and Nan Jiang, ICML2020.
- [Accountable Off-Policy Evaluation With Kernel Bellman Statistics](http://proceedings.mlr.press/v119/feng20d.html) by Yihao Feng, Tongzheng Ren, Ziyang Tang, and Qiang Liu, ICML2020.
- [Asymptotically Efficient Off-Policy Evaluation for Tabular Reinforcement Learning](http://proceedings.mlr.press/v108/yin20b.html) by Ming Yin and Yu-Xiang Wang, ICML2020.
- [Efficiently Breaking the Curse of Horizon in Off-Policy Evaluation with Double Reinforcement Learning](https://arxiv.org/abs/1909.05850) by Nathan Kallus and Masatoshi Uehara, arXiv2019.
- [Off-Policy Evaluation in Partially Observable Environments](https://ojs.aaai.org//index.php/AAAI/article/view/6590) by Guy Tennenholtz, Uri Shalit, and Shie Mannor, AAAI2019.
- [Intrinsically Efficient, Stable, and Bounded Off-Policy Evaluation for Reinforcement Learning](https://arxiv.org/abs/1906.03735) by Nathan Kallus, Masatoshi Uehara, NeurIPS2019.
- [Towards Optimal Off-Policy Evaluation for Reinforcement Learning with Marginalized Importance Sampling](https://papers.nips.cc/paper/2019/hash/4ffb0d2ba92f664c2281970110a2e071-Abstract.html) by Tengyang Xie, Yifei Ma, and Yu-Xiang Wang, NeuIPS2019.
- [Off-Policy Evaluation via Off-Policy Classification](https://papers.nips.cc/paper/2019/hash/b5b03f06271f8917685d14cea7c6c50a-Abstract.html), Alexander Irpan, Kanishka Rao, Konstantinos Bousmalis, Chris Harris, Julian Ibarz, and Sergey Levine, NeuIPS2019.
- [Off-Policy Evaluation and Learning from Logged Bandit Feedback: Error Reduction via Surrogate Policy](https://openreview.net/forum?id=HklKui0ct7) by Yuan Xie, Boyi Liu, Qiang Liu, Zhaoran Wang, Yuan Zhou, and Jian Peng, ICLR2019.
- [More Efficient Off-Policy Evaluation through Regularized Targeted Learning](http://proceedings.mlr.press/v97/bibaut19a.html) by Aurelien Bibaut, Ivana Malenica, Nikos Vlassis, and Mark Van Der Laan, ICML2019.
- [Combining parametric and nonparametric models for off-policy evaluation](http://proceedings.mlr.press/v97/gottesman19a.html) by Omer Gottesman, Yao Liu, Scott Sussex, Emma Brunskill, and Finale Doshi-Velez, ICML2019.
- [Counterfactual Off-Policy Evaluation with Gumbel-Max Structural Causal Models](http://proceedings.mlr.press/v97/oberst19a.html) by Michael Oberst and David Sontag, ICML2019.
- [Importance Sampling Policy Evaluation with an Estimated Behavior Policy](http://proceedings.mlr.press/v97/hanna19a.html) by Josiah Hanna, Scott Niekum, and Peter Stone, ICML2019.
- [When People Change their Mind: Off-Policy Evaluation in Non-Stationary Recommendation Environments](https://dl.acm.org/doi/10.1145/3289600.3290958) by Rolf Jagerman, Ilya Markov, and Maarten de Rijke, WSDM2019.
- [Representation Balancing MDPs for Off-policy Policy Evaluation](https://papers.nips.cc/paper/2018/hash/980ecd059122ce2e50136bda65c25e07-Abstract.html) by Yao Liu, Omer Gottesman, Aniruddh Raghu, Matthieu Komorowski, Aldo A. Faisal, Finale Doshi-Velez, and Emma Brunskill, NeuIPS2018.
- [Breaking the Curse of Horizon: Infinite-Horizon Off-Policy Estimation](https://papers.nips.cc/paper/2018/hash/dda04f9d634145a9c68d5dfe53b21272-Abstract.html) by Qiang Liu, Lihong Li, Ziyang Tang, and Dengyong Zhou, NeuIPS2018.
- [Confounding-Robust Policy Improvement](https://papers.nips.cc/paper/2018/hash/3a09a524440d44d7f19870070a5ad42f-Abstract.html) by Nathan Kallus and Angela Zhou, NeuIPS2018.
- [Balanced Policy Evaluation and Learning](https://papers.nips.cc/paper/2018/hash/6616758da438b02b8d360ad83a5b3d77-Abstract.html) by Nathan Kallus, NeuIPS2018.
- [More Robust Doubly Robust Off-policy Evaluation](https://arxiv.org/abs/1802.03493) by Mehrdad Farajtabar, Yinlam Chow, and Mohammad Ghavamzadeh, ICML2018.
- [Importance Sampling for Fair Policy Selection](https://people.cs.umass.edu/~pthomas/papers/Doroudi2017.pdf) by Shayan Doroudi, Philip Thomas, and Emma Brunskill, UAI2017.
- [Predictive Off-Policy Policy Evaluation for Nonstationary Decision Problems, with Applications to Digital Marketing](https://people.cs.umass.edu/~pthomas/papers/Thomas2017.pdf) by Philip S. Thomas, Georgios Theocharous, Mohammad Ghavamzadeh, Ishan Durugkar, and Emma Brunskill, AAAI2017.
- [Bootstrapping with Models: Confidence Intervals for Off-Policy Evaluation](https://arxiv.org/abs/1606.06126) by Josiah P. Hanna, Peter Stone, and Scott Niekum, AAAMS2016.
- [Doubly Robust Off-policy Value Evaluation for Reinforcement Learning](http://proceedings.mlr.press/v48/jiang16.html) by Nan Jiang and Lihong Li, ICML2016.
- [Data-Efficient Off-Policy Policy Evaluation for Reinforcement Learning](http://proceedings.mlr.press/v48/thomasa16.html) by Philip Thomas and Emma Brunskill, ICML2016.
- [High Confidence Off-Policy Evaluation](https://people.cs.umass.edu/~pthomas/papers/Thomas2015.pdf) by Philip S. Thomas, Georgios Theocharous, and Mohammad Ghavamzadeh.

### Off-Policy Evaluation: Benchmarks/Experiments/Applications
- [Benchmarks for Deep Off-Policy Evaluation](https://openreview.net/forum?id=kWSeGEeHvF8) by Justin Fu, Mohammad Norouzi, Ofir Nachum, George Tucker, ziyu wang, Alexander Novikov, Mengjiao Yang, Michael R Zhang, Yutian Chen, Aviral Kumar, Cosmin Paduraru, Sergey Levine and Thomas Paine, ICLR2021. [[code](https://github.com/google-research/deep_ope)]
- [Large-scale Open Dataset, Pipeline, and Benchmark for Bandit Algorithms](https://arxiv.org/abs/2008.07146) by Yuta Saito, Shunsuke Aihara, Megumi Matsutani, and Yusuke Narita, arXiv2020. [[software](https://github.com/st-tech/zr-obp)] [[public dataset](https://research.zozo.com/data.html)]
- [Off-Policy Evaluation of Probabilistic Identity Data in Lookalike Modeling](https://dl.acm.org/doi/10.1145/3289600.3291033) by Randell Cotta, Dan Jiang, Mingyang Hu, and Peizhou Liao, WSDM2019.
- [Offline Evaluation to Make Decisions About Playlist Recommendation](https://dl.acm.org/doi/10.1145/3289600.3291027) by Alois Gruson, Praveen Chandar, Christophe Charbuillet, James McInerney, Samantha Hansen, Damien Tardieu, and Ben Carterette, WSDM2019.
- [Towards a Fair Marketplace: Counterfactual Evaluation of the trade-off between Relevance, Fairness & Satisfaction in Recommendation Systems](https://dl.acm.org/doi/10.1145/3269206.3272027) by Rishabh Mehrotra, James McInerney, Hugues Bouchard, Mounia Lalmas, Fernando Diaz, CIKM2018.
- [Offline A/B testing for Recommender Systems](https://dl.acm.org/doi/10.1145/3159652.3159687) by Alexandre Gilotte, Clément Calauzènes, Thomas Nedelec, Alexandre Abraham, and Simon Dollé, WSDM2018.
- [Offline Comparative Evaluation with Incremental, Minimally-Invasive Online Feedback](https://dl.acm.org/doi/10.1145/3209978.3210050) by Ben Carterette and Praveen Chandar, SIGIR2018.

### Open Source Software

## Related Workshops

- [Reinforcement Learning Day 2021](https://www.microsoft.com/en-us/research/event/reinforcement-learning-day-2021/)
- [Offline Reinforcement Learning Workshop (NeurIPS 2020)](https://offline-rl-neurips.github.io/)
- [Reinforcement Learning from Batch Data and Simulation](https://simons.berkeley.edu/workshops/schedule/14240)
- [Virtual Conference on Reinforcement Learning for Real Life (RL4RealLife 2020)](https://sites.google.com/view/RL4RealLife)
- [Safety and Robustness in Decision Making (NeurIPS 2019)](https://sites.google.com/view/neurips19-safe-robust-workshop)

## Tutorials/Talks/Lectures

- [Offline RL](https://slideslive.com/38938455/offline-rl) by Nando de Freitas, NeurIPS2020 OfflineRL Workshop.
- [Learning a Multi-Agent Simulator from Offline Demonstrations](https://slideslive.com/38938458/learning-a-multiagent-simulator-from-offline-demonstrations) by Brandyn White, NeurIPS2020 OfflineRL Workshop.
- [Towards Reliable Validation and Evaluation for Offline RL](https://slideslive.com/38938459/towards-reliable-validation-and-evaluation-for-offline-rl) by Nan Jiang, NeurIPS2020 OfflineRL Workshop.
- [Batch RL Models Built for Validation](https://slideslive.com/38938457/batch-rl-models-built-for-validation) by Finale Doshi-Velez, NeurIPS2020 OfflineRL Workshop.
- [Offline Reinforcement Learning: From Algorithms to Practical Challenges](https://sites.google.com/view/offlinerltutorial-neurips2020/home) by Aviral Kumar and Sergey Levine, NeurIPS2020.
- [Statistically Efficient Offline Reinforcement Learning](https://youtu.be/n5ZoxT_WmHo) by Nathan Kallus, ARL Seminor2020.
- [Near Optimal Provable Uniform Convergence in Off-Policy Evaluation for Reinforcement Learning](https://youtu.be/FWZewbQykv4) by Yu-Xiang Wang, RL Theory Seminar2020.
- [Minimax-Optimal Off-Policy Evaluation with Linear Function Approximation](https://youtu.be/TX9KBofFZ8s) by Mengdi Wang, RL Theory Seminar2020.
- [Combining Statistical methods with Human Input for Evaluation and Optimization in Batch Settings](https://slideslive.com/38922630/combining-statistical-methods-with-human-input-for-evaluation-and-optimization-in-batch-settings) by Finale Doshi-Velez, NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
- [Efficiently Breaking the Curse of Horizon with Double Reinforcement Learning](https://slideslive.com/38922636/efficiently-breaking-the-curse-of-horizon-with-double-reinforcement-learning) by Nathan Kallus, NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
- [Scaling Probabilistically Safe Learning to Robotics](https://slideslive.com/38922637/scaling-probabilistically-safe-learning-to-robotics?locale=en) by Scott Niekum, NeurIPS2019 Workshop on Safety and Robustness in Decision Making.
