# FL-IoT
## 📚 Federated Learning for IoT Intrusion Detection

This repository is based on my understanding and implementation of the algorithms published in Paper : 

`Lazzarini, R.; Tianfield, H.; Charissis, V. Federated Learning for IoT Intrusion Detection. AI 2023, 4, 509-530. https://doi.org/10.3390/ai4030028`

## 🔨 Background
<details>
<summary>
Abstract from the Paper
</summary>
<br>
The number of Internet of Things (IoT) devices has increased considerably in the past few
years, resulting in a large growth of cyber attacks on IoT infrastructure. As part of a defense in depth
approach to cybersecurity, intrusion detection systems (IDSs) have acquired a key role in attempting
to detect malicious activities efficiently. Most modern approaches to IDS in IoT are based on machine
learning (ML) techniques. The majority of these are centralized, which implies the sharing of data
from source devices to a central server for classification. This presents potentially crucial issues
related to privacy of user data as well as challenges in data transfers due to their volumes. In this
article, we evaluate the use of federated learning (FL) as a method to implement intrusion detection in
IoT environments. FL is an alternative, distributed method to centralized ML models, which has seen
a surge of interest in IoT intrusion detection recently. In our implementation, we evaluate FL using a
shallow artificial neural network (ANN) as the shared model and federated averaging (FedAvg) as
the aggregation algorithm. The experiments are completed on the ToN_IoT and CICIDS2017 datasets
in binary and multiclass classification. Classification is performed by the distributed devices using
their own data. No sharing of data occurs among participants, maintaining data privacy. When
compared against a centralized approach, results have shown that a collaborative FL IDS can be an
efficient alternative, in terms of accuracy, precision, recall and F1-score, making it a viable option as
an IoT IDS. Additionally, with these results as baseline, we have evaluated alternative aggregation
algorithms, namely FedAvgM, FedAdam and FedAdagrad, in the same setting by using the Flower
FL framework. The results from the evaluation show that, in our scenario, FedAvg and FedAvgM
tend to perform better compared to the two adaptive algorithms, FedAdam and FedAdagrad. 
</details>

## ❓ Problem Statement
<details>
<summary></summary>
</details>

## 💽 Dataset
[ToN_IoT](https://research.unsw.edu.au/projects/toniot-datasets) <br>
[CICIDS2017](https://www.unb.ca/cic/datasets/ids-2017.html)

## 💡 Solution Statement
<details>
<summary></summary>
</details>


## 🎨 Project Design
