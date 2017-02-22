## Data Flow Diagram Dictionary

### Data Stores

  * License and Vulnerability Results: Database that contains any and all results from scanned software
  * NIST Vulnerability Database: National Institute of Standards and Technology database that contains known vulnerabilities for software
  * Policies: The corporate database for all policies
  
### Data Flows
 
  
  * License Results: Results from the License Scanner regarding any licenses for known software code
  * License and Vulnerability Results: All results from both the NIST Vulvernability Database and the License scanner
  * License and Vulnerability Info Request: Submission for information for both License and Vulnerabilities for particular software         package
  * NIST Vulnerability Results: Results from the NIST Vulvernability Database for known vulnerabilities
  * Policy Retrieval Request: Submission for policy from the Policies database
  * Policy Results: Any and all policy information from the Policies database
  * Policy Changes: Any and all policy updates or creation being submitted to the Policies database
  * Software Package: The developed software from the developer that is needs to be scanned for licenses and vulnerabilties
  * Software Package Name: Name of the software that is going to be submitted to the NIST Vulnerability database
  
### Processes

  * Create/Update Policy: Process of creating or updated a policy based off of license and vulnerability results 
  * License Scanner: Process of a software package being uploaded to the scanner to identify any license issues
  * License and Vulnerability Info Lookup: Process of receiving a request for information for license and vulnerabilities for a particular   software and outputting the results
  * Manage License and Vulnerability Information: Process of handling requests for license and vulnerabilities of particular software          packages, uploading software packages to scanners, uploading a name of software package to a database, and outputting the requested       results
  * Retrieve Policy: Process of receiving a request for any and all policies and outputting requested policies to manager
  
### Entities

  * Developer: The programmer of the software package
  * Manager: The head person who creates and updates policies based on license and vulnerability results after putting in the request for     the information
