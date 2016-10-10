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
A piece of software that is for commerical use.

* **NIST Vulnerability DB**:
A DB of known published vulnerabilities

* **Software Project**
A collection of software packages

* **Software Package**
Input for FOSSology scanning using the tool, it is compressed of a collection of files.
