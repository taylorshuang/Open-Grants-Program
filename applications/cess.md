# W3F Open Grant Proposal


* **Project Name:** Cumulus Encrypted Storage System (CESS)
* **Team Name:** CESS
* **Payment Address:** BTC or Ethereum (USDT/DAI) payment address. We don't accept payments for the program in other currencies at this stage. If this is an Ethereum address, please specify USDT or DAI. (e.g. 0x8920... (DAI))
* **Level:** 1


## Project Overview :page_facing_up:


### Overview

* Tag line: An infrastructure of decentralized cloud network facilities.
* Brief description: Cumulus Encrypted Storage System (CESS) is dedicated to develop a new global decentralized cloud storage online data sharing platform – a network infrastructure that is transparent, efficient, and equal opportunity to all members of the global community. The CESS data sharing protocol enables: a) data interoperability in manner of cross-platform, cross-collaboration, and cross-format, b) tracing and monitoring data trading market, and c) fair and transparent data profit rewarding. CESS will adopt a phased approach to implement the above goals.
* Indication 1: With the goal of entering Polkadot ecosystem, CESS will build a blockchain system based on Substrate directly, and plans to develop custom pallets on FRAME. In the future, CESS will consider integrating to Polkadot in the form of Parachain to create a new decentralized cloud storage ecosystem, establish a large-scale distributed storage network.
* Indication 2: With rapid advances of new computing technologies such as big data and machine learning, the value of humanity’s digital assets, the so-called “Digital Gold”, are being discovered. Explosively growing amount of data in cyberspace calls for new technologies of secure data storage and efficient data sharing. The challenges are to achieve secure storage, efficient sharing, and trading with data owner’s rights protection, but current solutions are complex and worrisome. Distributed storage networks can better drive the arrival of Web3.0 and are one of the underlying technical infrastructure of Web3.0.


### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

Mockups/designs of any UI components

* Global nodes: Display the global map and the number of global nodes of distributed storage network, and mark the location distribution of nodes according to coordinates; Display node list.

![Image](https://raw.githubusercontent.com/swowk/picsforcess/main/img1.png)

* My cloud disk: Personal storage space to view the files uploaded to the storage network; The list can be sorted by upload time, file name, file type and file size; Supports file download, share, property setting, deletion and other operations.
![Image](https://raw.githubusercontent.com/swowk/picsforcess/main/img2.png)

* File upload: Select the files to be stored and set the relevant storage parameters.

![Image](https://raw.githubusercontent.com/swowk/picsforcess/main/img3.png)

* Search for file: Search the whole network through keywords, and download the search results.
![Image](https://raw.githubusercontent.com/swowk/picsforcess/main/img4.png)

Documentation of core components, protocols, architecture, etc. to be deployed

* CESS is a high-speed, secure, scalable and decentralized cloud storage system. It can handle tens of thousands of transactions per second through parallel technology. Through Data slicing technology, it can achieve the secure storage of massive data, and it has the functions of Data confirmation and Data rights protection, which provides powerful data service ability. It provides DAPP with unlimited scalable storage capacity and perfect Data rights protection capability.

* As shown in the figure, CESS adopts a layered and loosely coupled design method, which is divided into Blockchain service layer, distributed storage resource layer, Distributed content distribution layer and Application layer. Among them, Blockchain service layer provides blockchain service of the whole CESS network, including encouraging idle storage resources, computing resources to join CESS network to provides data transaction, data confirmation and other services for the application layer. the Distributed storage resource layer uses virtualization technology to realize the integration and pooling of storage resources. The infrastructure consists of storage capacity miners and storage scheduling miners. The distributed content distribution layer uses content caching technology to realize the fast push of stored data, which is composed of data index miner and data distribution miner. By API node of Application layer, CESS can realize data storage service, blockchain service to support enterprise level SDK, data storage network disk and computational intelligence applications, etc. 
<div align=center><img width="72%" height="72%" src="https://raw.githubusercontent.com/swowk/picsforcess/main/img5.png"/></div>

### Ecosystem Fit

Polkadot provides a multi-chain application environment and a decentralized relay chain. Parachains can exchange information and transactions in a way without trust through relay chain of Polkadot. Through several proofs of storage, CESS can provide a public convenient and secure storage service for the users or Dapps which does not need to apply local storage so as to make reasonable use of the storage space.

CESS is a global decentralized cloud storage online data sharing platform. Similar projects in the Polkadot ecosystem include Ocean, DataHighway and Bluzelle. The differences between them are described in detail below.
* Ocean : It provides data processing, storage, computing and other services, helping to expand the data boundary, especially in the field of AI. It is designed for scale and uses blockchain technology to allow data to be shared and traded in a secure and transparent manner. Comparatively, the purpose of CESS is to provide users with high-quality and low-cost storage services without data processing.
* DataHighway：It is oriented to the Internet of things and provides data market at cross-chain level in the form of DAO. Although the project also supports the data storage function, it still serves the Internet of things.
* Bluzelle：It is a Byzantine fault-tolerant Web3 distributed database. Developers pay to read and write the database. Although data storage is its basic function, it is still a data rental market in essence.

## Team :busts_in_silhouette:

### Team members

* Name of team leader
* Names of team members 

### Contact

* **Contact Name:** Full name of the contact person in your team
* **Contact Email:** Contact email (e.g. john@duo.com)
* **Website:**

### Legal Structure

* **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
* **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)

### Team's experience

Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

### Team Code Repos

* https://github.com/Cumulus2021/CumulusSystem
* https://github.com/Cumulus2021/Whitepaper

### Team LinkedIn Profiles

* https://www.linkedin.com/<person_1>
* https://www.linkedin.com/<person_2>


## Development Roadmap :nut_and_bolt:


### Overview

* **Total Estimated Duration:** 4 months
* **Full-Time Equivalent (FTE):**  2
* **Total Costs:** 8,000 USD

### Milestone 1: Implement Substrate Modules

* **Estimated Duration:** 2 months
* **FTE:**  2
* **Costs:** 4,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can running substrate to support storage service. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article/Tutorial | We will publish an article and a tutorial that explains the work done as part of the grant. |
| 1a. | Substrate module: User Profile | We will create a Substrate module that will generate user profiles based on the user's subscription. |  
| 1b. | Substrate module: Authentication Status | We will create a Substrate module that will allow users to apply to authenticate accounts and query authentication status. |  
| 1c. | Substrate module: Storage | We will create a Substrate module that will process and upload user data, and support Integrity verification. |  
| 2. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain. |


### Milestone 2: Implement Storage Mining

* **Estimated Duration:** 1 month
* **FTE:**  2
* **Costs:** 2,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how proof of storage service works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 80%) to ensure functionality and robustness. In the guide we will describe how to run these tests. |
| 0d. | Article/Tutorial | We will publish an article and a tutorial that explains the work done as part of the grant. |
| 1a. | Stacked DRG Library | We will create a library for proving and verifying transactions, compatible with the substrate pallet. |  
| 1b. | zk-SNARK proofs | We will implement the algorithm to process the proof results from stacked DRG library. | 
| 2. | CESS Contracts | Develop CESS contract implement function of storage mining. | 
| 3. | Miner Client | Interactive with contract to implement mining supporting services. | 


### Milestone 3: Implement and Integrate CESS Applications

* **Estimated Duration:** 1 month
* **FTE:**  2
* **Costs:** 2,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | We will provide an application manual and a basic tutorial that introduces the functions of clients. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. |
| 0d. | Article/Tutorial | We will publish an article and a tutorial that explains the work done as part of the grant. |
| 1. | Cryptographic modules | We will implement the cryptographic modules including inner product functional encryption and the associated zero-knowledge proof for storage proof. |  
| 2. | UI Modules | We will design a user-friendly UI that supports both PC and mobile. | 
| 3. | File processing | We provide abundant file operation services, including file upload, download, share, delete, etc. | 
| 4. | Benchmark | Perform unit tests on the individual algorithms to ensure system safety. | 
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain. | 


## Future Plans

We will continue to improve the substrate-based CESS blockchain and provide reusable modules for the substrate FRAME, and provide the required storage space and verifications of storage proof for more users through Polkadot ecosystem since our project can verify the authenticity of storage space or data.

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website

We already have a design prototype and pilots, and no any teams who have already contributed financially to the project. We have not applied for any other grants with this exact project.
