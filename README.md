# JAXRS_Example_Database
> A RESTful API with pooled database connection

This simple RESTful API exposes data taken from an external database via a pooled JDBC connection.
 
## Usage

This is a *sample application* developed during the lectures of the  [**Sviluppo Web Avanzato course**](https://sviluppowebavanzato-univaq.github.io). The code is organized to best match the lecture topics and examples. It is not intended for production use and is not optimized in any way. 

*This example code will be shown and described approximately during the 10th lecture of the course, so wait to download it, since it may get updated in the meanwhile.*

## Installation

This is a Maven-based project. Simply download the code and open it in any Maven-enabled IDE such as Netbeans or Eclipse. 

The main branch contains the application version to be run on the **JakartaEE 10** platform inside the **Apache Tomcat 11** server. 
Note that you may need to *configure the project deploy settings* in your IDE based on the chosen platform/server: refer to the IDE help files to perform this step. For example, in Apache Netbeans, you must enter these settings in Project properties > Run.

 Finally, the application needs an external MySQL instance running on your system with a database configured as described in the DatabaseRes class.

---

![University of L'Aquila](https://www.disim.univaq.it/skins/aqua/img/logo2021-2.png)


