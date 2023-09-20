# TARP-Review-paper

Goal is to Create a high quality review paper 

|Team Members | Registration No.| Journals Split out |
|-----------| -------------| --------- |
| Saran D | 20MIC0148 | [Sciencedirect](https://www.sciencedirect.com/)
| Yuvarajan P | 20MIC0149| [Springer](https://www.springer.com/in) |
| Sriram G | 20MIC0159 | [ACM](https://dl.acm.org/) |
| Vignesh M | 20MIC0114 | [IEEE](https://ieeexplore.ieee.org/Xplore/home.jsp) |
| Joseph John Philip | 20MIC0140 | []() |


https://egateway.vit.ac.in/user/login

|Review Paper |Short Abstract |Drawbacks|Author |Year|
|:----|:----|:----|:----|:----|
|A Criminal Record Keeper System usingBlockchain [IEEE]|The study conducted by Khan et al., Hingorani et al., Shukla and others, and Dube et al. essentially revolved around the importance of secure record management in a police station. They successfully identified flaws such as the falsification and vulnerability of e-FIR data and proposed a blockchain solution utilizing technologies like Hyperledger fabric, Ethereum, and smart contracts. The creation of tamperproof, immutable records using these technologies sought to eradicate corruption, ensure data privacy, and promote justice for the user. To address user interface, a web-based GUI was developed to streamline data entry.|While the studies discuss promising solutions, they don't delve into potential challenges or risks. Constraint issues in learning and implementing new technologies like Ethereum or Hyperledger aren't mentioned. The cost and time requirements for migrating traditional databases to a blockchain system are not discussed. Dependence on digital infrastructure could also alienate individuals or regions with limited access. There’s also no discussion on dealing with potential errors or misinformation during data input, which could lead to irreversible issues due to the immutable nature of blockchain records. Additionally, the potential for smart contract vulnerabilities leading to data breaches isn't addressed.|Aditya Vijaykumar Singh1, Ashwin Omprakash Tiwari2, Shreyash Sanjay Singh3, and Vivian Brian Lobo41,2,3U.G. Student, 4Assistant Professor|2022|
|Criminal Record Keeping with Blockchain [JETIR]|This paper discusses the structure and functioning of a ledger in the context of Hyperledger Fabric blockchain. The ledger consists of two key components: a transaction log and a world state, both of which are updated through the deployment of chaincode. This chaincode is signed and turned into an unchangeable package, run as a Docker image for stability. Transactions run through channels, and each peer can handle multiple channels. Certificate generation is managed with a Fabric CA service, and persistence venues include MySQL, PostgreSQL, or LDAP server. Lastly, the Orderer service ensures transaction consistency across participants.|The paper does not provide specific inefficiencies or limitations of the system. However, a potential drawback can be the complexity and static nature of advanced certificate creation. Creating advanced certificates dynamically can be complicated and costly for large-scale applications. Furthermore, the requirement of running chaincode as a Docker image for each transaction might lead to scalability issues, especially if the number of transactions significantly grows. And, depending on the efficiency of the Fabric CA, the generation of certificates might also become a bottleneck in the system. Lastly, the efficacy of PostgreSQL, MySQL, and LDAP as persistence mechanisms isn't extensively evaluated.|1 Purvi Makwana,  2 Dr.Priyanka Sharma 1 Post Graduation, Cyber Security, M.Tech, Raksha Shakti University, Ahmedabad, Gujarat, India 2 Assistant Professor, Raksha Shakti University, Ahmedabad, Gujarat, India|2019|
