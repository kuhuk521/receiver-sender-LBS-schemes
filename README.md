# Receiver and Sender friendly Location based service schemes using Public Key Encryption (PKE)

The widespread adoption of mobile devices with location capabilities has increased the demand for Location Based Services (LBS). In the LBS scheme, the vehicle users submit their query to the LBS server, which in return responds to the requested query. However, conventional LBS schemes pose threats to both the vehicle users' and the LBS servers' data privacy. Existing solutions, such as k-anonymity, Dummy sequence and Caching schemes overlook the critical aspect of the data privacy of the LBS server and the computational constraints of vehicle users. Here, we propose a receiver-efficient scheme using Oblivious Transfer (OT) with ElGamal with an Elliptic Curve Cryptosystem (ECC). Our scheme aims to safeguard the query and location privacy of vehicle users, and the LBS servers' data privacy, while also maintaining constant-time computations at the receivers' end. The LBS server may occasionally get overloaded as a result of heavy traffic or a demand for query data.  Hence, we further propose a scheme for scenarios where the sender is computationally overloaded. We use extended Schnoor’s ring signature with ECC to achieve data privacy of the LBS server and identity privacy of the vehicle user, while maintaining constant time computations at the senders’ end. 
Further, to effectively tackle large number of locations coordinates n, we can implement OT extension to divide n into smaller bases for effective computation and lesser retrieval time.

## Receiver-efficient proposed scheme architecture 
![Screenshot 2024-04-23 221131](https://github.com/kuhuk521/receiver-sender-LBS-schemes/assets/79625787/f21d7a5d-ef11-471d-8da5-c8e544ddc3e4)


## Sender-efficient proposed scheme architecture
![Screenshot 2024-04-23 230742](https://github.com/kuhuk521/receiver-sender-LBS-schemes/assets/79625787/13610ffe-ed68-4393-8c1f-fa5dce6d64f4)


