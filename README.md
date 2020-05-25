## **QoE Prediction**

Through the massive collection of KPI that quantify the performance of a mobile access network, a practical approach has been developed for the **prediction of the Quality of Experience (QoE)** based on measurements performed by common smartphones and on Machine Learning (ML) algorithms.

To collect a large number of KPI, third-party web and mobile application have been used with the aim to make several test phone call and store the RAN principal KPIs.

In particular, the performance of different QoE prediction models has been compared in terms of two main parameters: the Mean Opinion Score (MOS) and the Service Acceptability (SA).
The first parameter requires that the algorithms go in search of the solution of a "multi-class" classification problem, while the second concerns a binary classification problem.

## **KPIs**

*   Received Signal [dBm]
*   Speed [m/s]
*   Distance from site [m]
*   Call Test Duration [s]
*   Call Test Result
*   Technology (2G/3G/4G)
*   Call Test Setup [s]

## **Software and Libraries**

*   Nteract (https://nteract.io/)
*   Scikit-Learn (https://scikit-learn.org/stable/)
*   XGBOOST (https://xgboost.readthedocs.io/en/latest/)
*   Pandas (https://pandas.pydata.org/)
*   Pandas-ML (https://github.com/pandas-ml/pandas-ml)

## **Results**

Below you can find the comparison in terms of Accuracy for different models:

**MOS Prediction**
![](img/results_mos.png)

**SA Prediction**
![](img/results_sa.png)

## **References**

[1] J. Pérez-Romero, O. Sallent, R. Ferrús, R. Agustí, “Artificial Intelligence-based 5G Network Capacity Planning and Operation”, International Symposium on Wireless Communication Systems (ISWCS), pp. 246-250, 2015.
[2] V. Aggarwal, E. Halepovic, J. Pang, S. Venkataraman, H. Yan, “Prometheus: Toward Quality-of-Experience Estimation for Mobile Apps from Passive Network Measurements”, in ACM HotMobile’14, February 26–27, 2014.
[3] W.S. McCulloch and W. Pitts, “A Logical Calculus of the Ideas Imminent in Nervous Activity”, Bulletin of Mathematical Biophysics, 5, 1943
[4] F. Rosenblatt, (1958), “The perceptron: a probabilistic model for information storage and organization in the brain”, Psychological Review, 65 (6)
[5] J. von Neumann (1958) “The computer and the brain”
[6] B. Widrow and M. E. Hoff, “Adaptive switching circuits,” IRE WESCON, Conv. Rec. IRE, New York, pp. 96-104, 1960.
[7] B. Widrow and M.E. Hoff, “Associative storage and retrieval of digital information in networks of adaptive neurons”, Biol. Prototypes Synthe. Syst., E. E. Benard and M. R. Kane, Eds. New York Plenum Press, 1962, vol. 1.
[8] A. Newell, "Perceptrons. An Introduction to Computational Geometry. Marvin Minsky and Seymour Papert. M.I.T. Press, Cambridge, Mass., 1969. vi + 258 pp., illus. Cloth, $12; paper, $4.95," Science, vol. 165, pp. 780-782, August 22, 1969
[9] K. Fukushima, (1980). "Neocognitron: A Self-Organizing Neural Network Model for a Mechanism of Pattern: The Recognitron Unaffected by Shift in Position", Biological Cybernetics. 36: 193–202.
[10] D. Rumelhart, G. Hinton, R. Williams (9 October 1986). "Learning representations by back-propagating errors". Nature. 323: 533–536.
[11] Mobiperf, “Mobiperf, Measuring Network Performance on Mobile Platforms”, 2013.
88
[12] A. Nikravesh, H. Yao, S. Xu, D. Choffnes and Z. M. Mao, “Mobilyzer: An open platform for controllable mobile network measurements”, in MobiSys, 2015.
[13] C. Kreibich, N. Weaver, B. Nechaev and V. Paxson, “Netalyzr: Illuminating the edge network”, in ACM IMC, 2010.
[14] K. Chen, C. Tu, and W. Xiao, “OneClick: A framework for measuring network quality of experience”, In IEEE, INFOCOM, 2009.
[15] D. Joumblatt, J. Chandrashekar, B. Kveton, N. Taft, and R. Teixeira, “Predicting user dissatisfaction with Internet application performance at end-hosts”, In INFOCOM, 2013.
[16] Int. Telecommunication Unit, “ITU-T Rec. P.800: Methods for Subjective Determination of Transmission Quality”, 1996.
[17] N. Bhatia, “Survey of Nearest Neighbor Techniques”, International Journal of Computer Science and Information Security, Vol. 8, No. 2, 2010.
[18] B. E. Boser, I. Guyon, and V. Vapnik, “A training algorithm for optimal margin classifiers”, In Proceedings of the Fifth Annual Workshop on Computational Learning Theory, pages 144–152. ACM Press, 1992.
[19] C. Cortes and V. Vapnik, “Support-vector network. Machine Learning”, 20:273–297, 1995.
[20] J.R. Quinlan, “Induction of decision trees”, Machine learning, 1986 – Springer
[21] J.R. Quinlan, “C4. 5: programs for machine learning”, Morgan Kaufmann, 1993.
[22] L. Breiman, J. Friedman, R. Olshen, and C. Stone, “Classification and Regression Trees”, Wadsworth, Belmont, CA, 1984.
[23] T. G. Dietterich, “An Experimental Comparison of Three Methods for Constructing Ensembles of Decision Trees: Bagging, Boosting, and Randomization”, in Machine Learning, 1-22 (1999).
[24] Ron Kohavi, “A Study of Cross-Validation and Bootstrap for Accuracy Estimation and Model Selection”, in International Joint Conference on Artificial Intelligence (IJCAI), 1995.
[25] Metricell, http://metricell.co.uk/
[26] ETSI, http://www.etsi.org/
89
[27] Int. Telecommunication Unit, “ITU-T Rec. P.863: Perceptual Objective Listening Quality Assessment”, 2014.
[28] NTERACT, https://nteract.io/
[29] “Scikit-Learn, Machine Learning in Python”, http://scikit-learn.org/stable/
[30] T. Chen, C. Guestrin, “XGBoost: A Scalable Tree Boosting System”, in KDD '16 Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, Pages 785-794
[31] “PANDAS: Python Data Analysis Library”, https://pandas.pydata.org/
[32] https://github.com/pandas-ml
[33] P. Casas, A. D’Alconzo, et al., “Predicting QoE in Cellular Networks using Machine Learning and in-Smartphone measurements”, in Ninth International Conference on Quality of Multimedia Experience (QoMEX), 2017.
[34] P. Casas, M. Seufert, F. Wamser, B. Gardlo, A. Sackl and R. Schatz, “Monitoring Quality of Experience in Cellular Networks from the End-Devices”, in IEEE Transactions on Network and Service Management, vol. 13, no. 2, June 2016.