#DFD Dictionary

##Entities

* **Developer**: 
Stakeholder who provides the relevant file/package level information.

* **Manager**:
Stakeholder who receives clear and relevant project information.

##Processes

* **Return Data to Developer**:
This process is responsible for managing connection between the Developer and Identifying OSS components. This process is responsible to return all OSS components presented in Software package an License Information.

* **Revise Software Policy**:
This process is responsibile for managing connection between the Developer and the Software Policy Database. This process is responsible to send any decisions to add/modify software policy from the developer.

* **Managing Software Package for License Scanning and Vulnerabilities**:
This process is responsible for managing connections between the Developer, several processes and the NIST Vulernability Database. This process is responsibile for retrieving software package vulerability results and Licenses information to the Developer. 

* **Managing Software Package Policy Information**:
This process is responsible for managing conections between the Developer, the Manager and the Software Policy Database. This process is responsible for retrieving software package policy information results to the Developer and the Manager.

* **Scan for Licenses**
This process is responsible for scan the licenses in the software package and return the results to the previous process.

* **Query the Database to retrieve Software Project Licenses and Vulnerability Information**: 
This process is responsible for managing the connection between the Manager and the Software License and Vulnerabilities datastore. This process is responsible for retrieving software project licenses and vulnerability information and returning it to the Manager.

##Data Flows

* **Software Package**:
A piece of software that is for commerical use, it is providede by the Developer as the input.

* **Software Package Name**:
The name of the Software Package provided by the Developer.

* **Software Package Policy Information Request**:
The request from the Developer or the Manager, asking for the the Software Package Policy Information from the corresponding datastore.

* **Software Package Policy Information Results**:
The results given to the Developer or the Manager, after they successfully requested the Software Package Policy Information from the corresponding datastore.

* **Decision to add/change software policy**:
The decision made by the manager to submit or modifiy policy documents in the corresponding datastore.

* **Software Package Vulnerability Results**
The vulnerability information that can be retrieved from the NIST Vulnerability datastore.

* **Software Package License Results**
The licenses information regarding to the software package provided.

* **Software Package License and Vulnerability Results**
The vulnerability information and licenses information regarding to the software package provided.

* **Software Project License and Vulnerability Information Results**
All the vulnerability information and licenses information regarding to the all software packages provided in the software project. 

* **Software Project License and Vulnerability Information Request**
The request from the manager, asking for all the vulnerability information and licenses information regarding to the all software packages provided in the software project. 

##Data Repositories

* **NIST Vulnerability DB**:
A database of known published vulnerabilities.

* **Software Policy DB**:
A database storing all the policy documents of the software packages.

* **Software License and Vulnerabilities DB**:
A database storing all the vulnerability information and licenses information of software packages.
