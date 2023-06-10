# Online-Biometrically-Verified-Electronic-Voting-System

General elections in Pakistan are held for 272 general seats in the National Assembly and 593 general seats in the four Provincial Assemblies on party basis every five years, or when warranted. These elections are held on adult franchise basis by secret paper ballot. For voting, the voter has to physically report to the allotted polling station of his constituency. Votes are cast on separate ballots for the National and Provincial Assemblies. Although fingerprints of the voters are taken at the time of voting, yet there is no system for real-time biometric verification. Even after the conduct of elections, biometric verification is unconvincing due to procedural and technical limitations. After the polling concludes, the compilation of results is always subject to procedural delays and objections regarding their veracity.

The project ONLINE BIOMETRICALLY VERIFIED ELECTRONIC VOTING SYSTEM (OBV-EVS) aims at remodeling the voting system to address the shortcomings of present manual system remaining within the existing statutory framework.

#### PROJECT GOALS
The project seeks to achieve following goals:
*	Develop a prototype web-based application to simulate the electoral process of general elections in Pakistan incorporating biometric verification.
*	Eliminate the requirement of physical presence in one’s constituency for voting, also allowing Pakistani expatriates to exercise their right of vote.
*	Incorporate adequate safeguards in the software to ensure free, fair and impartial elections.
*	Accrue benefits of object-oriented programming.
*	To achieve the learning outcomes mentioned herein.


#### PROJECT ARCHITECTURE AND APPROACH
##### APPROACH
The software adopts model-view-controller (MVC) approach.
###### JAVA CLASSES
*	The various data entities formed models at the server end. These models are used for passing information between various modules of the software as well as for facilitating writing and reading data to the database.
###### SERVLETS
*	Java servlets form the controller part to implement the software logic. Major servlets include, LoginServlet, BiometricVerificationServlet, CandidateServlet, ConstituencyServlet, EditUserServlet, ScheduleServlet, ResultsServlet, VoteCastingServlet.
###### JSPS
*	JSPs and HTML documents form the view part. Major JSPs include VoterVerification, BiometricVerification, Candidates, Constituencies, Parties, VoteCasting, and Results. 
###### HTML (HYPERTEXT MARKUP LANGUAGE)
*	HTML has been used for providing basic structure of webpages assisted by Cascading Style Sheets (CSS) to style and design webpages and its content.
###### CASCADING STYLE SHEETS (CSS)
*	Separate CSS files allow multiple JSPs to share CSS content, hence ensuring reusability and reduce complexity. 
###### JAVASCRIPT
*	JavaScripts have been used to call APIs of the biometric sensor as well as for data validations. Moreover, JavaScript has provided users with interface interactivity such as the sliding of forms and other transitions, creating powerful client-side experience.

##### DEVELOPMENT ENVIRONMENT AND SOFTWARE USED
###### JDK 13.0.2
*	Java development kit version 13.0.2 provides the compiler and other essential tools for development of Java applications.
###### APACHE NETBEANS IDE 11.3
*	NetBeans is the official IDE for Java 8. The IDE facilitates programmers to build Java desktop, mobile, and web applications by offering a range of potent tools and features. 
###### TOMCAT 9.0 SERVER
*	Apache Tomcat Server version 9 has been used. It is a simple to use web server which can be used at commercial scale also.
###### DATABASE
*	MS Access 2016 was used to create a database named “EVoting.accdb”. The database contains tables for storing user, constituencies, voters, political parties, candidates and votes. Other tables include those implementing many-to-many relationships.

Demo is also available in the uploaded files

![image](https://github.com/sanazehra2001/OBV-EVS/assets/76579833/bbb93da9-810a-4928-a642-45cb2e917b94)

<img width="609" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/f861dd6e-8631-453e-94a4-ff6114049508">

<img width="609" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/c04567f8-9235-465f-bc67-927e8249e1f0">

###### Login Details:
| Username | User Type | Password |
--- | --- | --- 
| mubeen732 | ECP | lAkBQMz511 |
| awais193 | Returning officer | oM7wCMnZoq |
| shahid800 | Polling officer | 8hJFu4fdiH |

ECP can access and modify Election Schedule, Constituencies, Parties and Returning Officers
<img width="612" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/fe6f563a-d12f-4b4e-abac-f5e66723e097">

Returning Officer can view and modify Candidates and Polling Officers
<img width="607" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/bf1e0575-065c-48c1-a0dc-958620eaae7a">

Polling officer will the account on the day of Election. Officer will be responisble for casting votes. He/she will enter the CNIC of citizen and select the fingerprint reader to capture the thumb impression
<img width="610" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/965169d2-dfa4-47cb-aa06-f0c3b445f0d2">

If the CNIC and thumb impression are verified, user will be directed to the form from where he / she can cast their vote.
<img width="607" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/cf1b948b-48c7-4d0d-95c7-a2a48ff5bd52">

Voter can also verify their polling station details  from the website
<img width="608" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/7a083048-ef37-48be-a0c3-010692b761da">

<img width="609" alt="image" src="https://github.com/sanazehra2001/OBV-EVS/assets/76579833/0a84b4a0-1b44-4636-8f9b-b7359bae8f91">


