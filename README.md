Data Modelling for the Evaluation of Virtualized Network Functions Resource Allocation Algorithms

Network Function Virtualization (NFV) proposes to move packet processing from dedicated hardware middle-boxes to software running on commodity servers: virtualized Network Function (NFs) (i.e, Firewall, Proxy, Intrusion Detection System etc.). We have been developing an experimental platform called Network Function Center (NFC) to study issues related to NFV and NFs, assuming that the NFC will deliver virtualized NFs as a service to clients on a subscription basis. Our studies specially focus on dynamic resource allocation for NFs and we have proposed two new resource allocation algorithms based on Genetic Programming (GP) [1] and currently working on another algorithm based on Iterative Local Search. For a more realistic evaluation of these algorithms, testing data is a fundamental component, but unfortunately, public traffic data specifically referring to virtualized NFs chains is not readily available. Therefore, we developed a model to generate the specific data we needed, based on the available general traffic data [2]. In this project, we present all the details about general data we used and how we modelled this general data into the specific data we wanted, with along the software we used and the assumptions we made during the data modelling process. Finally we present the results obtained during the evaluation of our GP algorithm, based on data traffic generated with our model, so that the evaluation results of our algorithms can be easily reproduced. 


[1] W. Rankothge, J. Ma, F. Le, A. Russo, and J. Lobo, “Towards making network function virtualization a cloud computing service,” in IM 2015


[2] W. Rankothge, F. Le, A. Russo, and J. Lobo, “Experimental results on the use of genetic algorithms for scaling virtualized network functions,” in IEEE SDN/NFV 2015.
