# Constraint-Aware-DL-For-Resource-Allocation-in-D2D-Communication

## Abstract
Device to Device (D2D) Communication in cellular networks allows direct communication between users without the traffic going through any Base station or core network infrastructure. With the main advantage of providing ultra low latency communication, D2D is a promising technology. In D2D, resource allocation is one of the crucial areas of research, since multiple users share the subchannels which introduces the factor of interference. Thus many algorithms have been developed in pursuit of providing efficient management and assignment of D2D pairs to subchannels. The algorithms which are mainly designed to solve optimization problems give optimal values, but the trade off of such algorithms is the time complexity involved.

In order to overcome this issue, a deep learning based solution is proposed. Lagrangian based neural networks are developed to solve the optimization problem in a data driven manner. Other solutions including Recurrent Neural Networks are also experimented with. The specific problem of resource allocation, that can be designed as a knapsack problem, forms the dataset upon which the experiments are carried out.

## File Structure
 - Constraint And No Constraint Learning : Constains code that show a NN is capable of learning optimization alogorithms without constraint like to and with constraint like Knapsack problem
 - Vanilla NN : A basic NN used for multiclass classification. This folder also contains other ML models tested on the data.
 - RNN : Recurrent Neural networks with LSTM, Bidirectional RNN and Encoder-Decoder trials
 - Lagrangian Loss NN : Final NN model with custom loss function that implements the constraints in the form of "Soft Constraints".

## Code
The above code is written in Python3 and using Tensorflow as the DL library

## Understanding Math
The Mathematics and the work can be understood better by reading the [report](https://github.com/venkatramnank/Constraint-Aware-DL-For-Resource-Allocation-in-D2D-Comm/blob/main/IISC_report_VenkatRamnanK.docx.pdf)

## Acknowledgments
This project is done as a part of the internship at the **Next Generation labs at the ECE Department of the Indian Institute Science**. I thank Prof Neelesh B Mehta and Bala Venkata Ramulu Gorantla for continuous guidance, teaching, and encouragement throughout the internship period and the project.

## Important papers to look into
[A Primal-Dual Formulation for Deep Learning with Constraints](https://www.cse.iitd.ac.in/~parags/papers/conference/2019/pdfdlc-nips19.pdf)

[Lagrangian Duality for Constrained Deep Learning](https://arxiv.org/pdf/2001.09394.pdf)

[Deep Learning based Wireless Resource Allocation with Application to Vehicular Networks](https://arxiv.org/abs/1907.03289)

## Future work
Since learning with constraints is a new and highly researched topic, a lot of work is going in this direction. The above experiments work but do not produce the expected results. Other learning methods like Reinforcement Learning can be looked into.

## Contact
For any doubts or contribution please contact venkatramnank@gmail.com
