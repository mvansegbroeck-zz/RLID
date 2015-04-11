# Rapid Language Identification (RLID)

Source code in support of the paper:

*Maarten Van Segbroeck, Ruchir Travadi and Shrikanth S. Narayanan, Rapid Language Identification (2015), in: IEEE/ACM Transactions on Audio, Speech and Language Processing.*

**Abstract**

A critical challenge to automatic language identification (LID) is achieving accurate performance with the shortest possible speech segment in a rapid fashion. The accuracy to correctly identify the spoken language is highly sensitive to the duration of speech and is bounded by the amount of information available. The proposed approach for rapid language identification transforms the utterances to a low dimensional ivector representation upon which language classification methods are applied. In order to meet the challenges involved in rapidly making reliable decisions about the spoken language, a highly accurate and computationally efficient framework of ivector extraction is proposed. The LID framework integrates the approach of Universal Background Model (UBM) fused total variability modeling. UBM-fused modeling yields the estimation of a more discriminant, single i-vector space. This way, it is also a computationally more efficient alternative than system level fusion. A further reduction in equal error rate is achieved by training the i-vector model on long duration speech utterances and by the deployment of a robust feature extraction scheme that aims to capture the relevant language cues under various acoustic conditions. Evaluation results on the DARPA RATS data corpus suggest the potential of performing successful automated language identification at the level of one second of speech or even shorter duration.
