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
