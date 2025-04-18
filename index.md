---
layout: default
---

<link rel="stylesheet" href="/styles.css">

# E-Portfolio

## Welcome
Hello my name is Derek Clark and welcome to my E-portfolio. The purpose of this E-portfolio is to not only demonstrate my ability to develop a fully fledged working application but identify weaknesses and imporvements that can be made to enhance the artifact.  Encompassed in this portfolio are three unqiue artifacts that fall under three distinct software development categories. These three distinct categories are [Software Design & Engineering](#artifact-1-software-design--engineering) , [Algorithms & Data Structures](artifact-2-algorithms-data-structures) , and lastly [Databases](artifact-3-databases). 

Additionally, I have included a [**_code review video_**](#code-review) that was recorded prior to the enhanced works completion detailing the planned enhancement and how it will imrove the application.

In the next section of the E-portfolio I have decided to include a professional self assesment reflecting on the work I have done to complete this capstone project and my experience in the computer science program at SNHU.

---



## Professional Self Assesment
Completing the coursework throughout the SNHU computer science curriculum has allowed me to develop artifacts in which I can use to support my technological abilities including the use of relevant tools and practices that are commonly utilized in the software development field . Developing this E-portfolio has allowed me to take these previous works, showcase the work done, and reflect on the changes made to enhance them. Reviewing and reflecting upon past work during the construction of this E-Portfolio has granted me the opportunity to identify flaws, vulnerabilities, and weaknesses within these past works that I may have not previously been aware of. Throughout the SNHU computer science program I had the opportunity to work on many projects that involved developing solutions for real world problems both individually and as a group. Through developing these projects I have discovered many core software development principles and values such as gaining a deeper appreciation for the planning and testing phases of the software development life cycle and learning how to effectively gather user feedback to generate user-centric designs. My experience with full stack web development, databases, android development, and agile methodologies have prepared me to contribute meaningfully in various computer science related fields. 

Throughout my time at SNHU I developed projects utilizing different tech stacks and languages which allowed me to not only understand them individually but understand how to program down to the fundamentals. For example, in my data structures and algorithms course I had created various projects utilizing c++ in which I had to extract data from CSV files, insert the relevant data into the appropriate data structure, and perform operations on the data such as querying, sorting, and updating. Although this course only had us develop these projects utilizing c++ the course had given me the fundamental base knowledge of the different types of data structures, what their benefits and weaknesses are, and the understanding of time/space complexities which will benefit me in any job that involves managing data efficiently and identifying optimal computing solutions. 

On the non technical side I also developed soft skills throughout the SNHU computer science program like effective communication, teamwork, and how to properly collect user feedback. One example in which I had to collaborate with a team and communicate with stakeholders was during my enrollment in the Software Development Lifecycle course. Participating in this course meant that I would have to work with a team of peers in which we would each select a role in the SDLC such as Product Manager, QA tester, Developer, and Scrum Master. The role I had selected was of product manager to which I had to communicate back and forth with my team my interview notes from my interview with stakeholder and potential users of our application detailing requirements and expectations of the application. 

To summarize, the main goal of this E-Portfolio and the artifacts that reside within it is to showcase my relevant skills and experience designing and developing software, working with data structures/algorithms, and creating/managing databases. These three core skills are what I believe encompass software development and specifically play a major role in web development where a web application is designed and developed incorporating data and managing the data efficiently. The three artifacts included in this E-Portfolio show my progress in different aspects of computer science that are common in the field of software development.

### Skills Showcased
| **Hard Skills** | **Soft Skills** |
| --- | ----------- |
| ReactJs | Teamwork |
| NodeJs | Stakeholder |
| MongoDB | Adaptability |
| Git | ProblemSolving |
| Data| CriticalThinking |
| SQLite | Time |

| **Hard Skills** | **Soft Skills** |
| --- | ----------- |
| ReactJs | Teamwork and Collabortion |
| NodeJs | Stakeholder Communication |
| MongoDB | Adaptability |
| Git | Problem Solving |



---

## Code Review

Code reviews are an important and common practice in the field of software development allowing for a deeper more thruough look through of the code to identify possible weaknesses, vulnerabilities, and ways in which the code can be improved. The following code review video was performed by me identifying enhancements that can be made to the three artifacts included in this E-portfolio, why I have chosen the enhancements/how the enhancement will improve the artifact, and finally what are my plans for implementing the planned enhancements. The code review video demonstrates my growth as a software developer and my ability to aknowledge my own faults and improve upon them with my new found knowledge.
[![Watch the video](https://img.youtube.com/vi/MguxJ_hu0xo/0.jpg)](https://www.youtube.com/watch?v=MguxJ_hu0xo)

---

## Artifact 1: Software Design & Engineering
[**Original artifact repo**](https://github.com/DerekVClark/app)

The artifact that I have chosen to enhance and showcase in the category of software design and engineering is my CS-360 final project. This project originally had required me tro develop a mockup design for an inventory management application based on requirements I had gathered from mock interviews with store management personel, warehouse workers, and truck delivery drivers. The general needs of these three user types can be broken down into three core functionalities, the ability to sign in to the application using user credentials, the ability to perform CRUD functionality to inventory items (Including adding, updating, and deleting items), and recieve SMS text messages when an item in inventories quanitity is equal to zero. Following the gethering of these user requirements I was tasked with developing an adroid application utilizing the android studio IDE for constructing the user interface and communicating with an SQLite database to manage inventory items using local storage.

[**Enhanced artifact repo branch**](https://github.com/DerekVClark/app/tree/feature/barcodeScanning)

Although all user requirements were fulfilled within the scope of the original app I had identified that manual input of inventory item data was highly inefficient and users of the application may not have an easy time remembering item data like the items ID to keep track of items correctly. The solution/enhancement that I had identified through my code review is the integration of the Android devices camera allowing for users to navigate to a scan barcode page, point their camera at an items barcode, and automatically fill in item data in order to add the item to the database.
### Why I have chosen this artifact
The reasoning behind my inclusion of this project in my E-Portfolio is that I believe it showcases some of my best work in the overall category of software design and engineering developing a working product with a user friendly design to solve a real world problem. The project not only demonstrates my ability to develop an android application that utilizes a database but also my ability to gather user requirements from user stories, design mockup designs, and design a unique user interface that complies with androids [**best UI/UX design practices**](https://developer.android.com/design/ui/mobile/guides/foundations/accessibility). I believe that overall this project demonstrates my ability to develop computing science solutions for real world problems accurately reflecting the type of work that I will be doing in the future of gathering software requirements to determine the functionality any components of the software needing to be constructed, iterating through software design diagrams for visual design/user navigation, then implementing solutions that solve user problems. A specific component included in this artifact that I believe showcases my skills and ability in software development is the barcode scanning screen. The barcode scanning screen begins by requesting camera permissions from the user demonstrating standard requirement compliance, then utilizes the camera hardware component on the android device to preview the devices back facing camera view, then the code utilizes camerax and google ML kit to obtain and analyze image frames taken from the capture to determine if a barcode exists within it. The code then takes this barcode and extracts data from it to be used for storing the item in the database. The skills and ability demonstarted by this component is my ability to integrate software with hardware, utilize external libraraies, and implement computing solutions to assist in solving user related problems. This artifact has continuously been improved allowing for the user to add items via manual data input or the use of the barcode scanning functionality along with easy navigation between pages and security measure incorporating through a login screen to safeguard user data. 
### What I learned
Throughout my work enhancing this artifact I have learned alot about integrating physical hadware components like the android camera into software functionality and also the exitsence of google's machine learning kit. Personally I have also learned that I am able to accomplish alot even when it comes to working with very loose guidelines and resources researching my own answers to questions I had during development and developing solutions based on the information I gathered. The challenges that I faced when implementing these enhancements was initially setting up the camera to be used in the application. Luckily I discovered the camerax library documentation which gave me a rough outline as to how to set up the camera but was not the clearest in terms of what I needed it for so I had to do some improvisation. Additionally I also had trouble integrating the image analysis functionality included in the ml kit as many of example and documentation was written in Kotlin when I was utilizing Java.

### Course outcomes checklist
- [x] (Partially) Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
- [x] Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
- [x] Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.
- [x] Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
- [x] (Partially) Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

Overall this artifact enhancement meets many of the capstone course outcomes except partially for security as the android application does incroporate a login page for ensuring each inventory database is locked behind a user login but the user credentials are stored locally making it easily obtainable if the device were to be iniltrated. As for the first outcome of collaboration this project was done individually by myself but the code is hosted on github with proper commit messages and comments allowing for others to download it and build upon it if desired.

---

## Artifact 2: Algorithms & Data Structures

[**Original Artifact Repo**](https://github.com/DerekVClark/Class-Data-Management)

The original artifact I have selected to demonstarte my ability and knowledge of the algorithms and data structures category is my CS-300 Class data Management project. This artifact was written entirely in c++ and was developed to provide a solution for a mock college to be utilized by academic advisors to allow for easy sortability of course data, easy querying of course information, and create a centralized data center for all course data previously organized in csv files. The solution this artifact provided was that it loaded data from the previously used csv file by parsing course data including ID, title, and list of prerequisite courses into the vector data structure. This vector data structure was utilized for both querying and sorting course data and while sorting was highly efficient as quick sort can be applied querying data proved to be highly inefficient utilizing the linear search algorithm which would only require more and more time to search for a specific course as the course list grew.

[**Enhanced artifact repo branch**](https://github.com/DerekVClark/Class-Data-Management/tree/enhancedBranch)
### Why I have chosen this artifact
The reason why I have decided to include this artifact in my E-Portfolio is because it demnstartes an efficient use of data structures for handling real world data and effective use of algorithms for providing real world solutions. Additionally, I believe the enhancement for this work demonstartes my growth in the realm of data structures and algorithms identifying the trade offs of using different structures and algorithms for particular problems. The improvement that I ended up making dealt with the inefficiency of utilizing vectors for querying course data through linear search. The improvement that I had identified was utilizing an unordered map data structure along side the vector which can gold key value pairs to which the users queried id would directly be associated with course data that can easily be retrived from a map with the same id to course data association. The reason I decided to not completely remove the vector is beause although maps can efficiently query data an unordered map does not sort data efficiently like the vector does with the quick sort algorithm. I had also enhanced vulnerability detection and mitigation through implementing exception handling, handling errors present in the code without crashing the program. the specific components within it that showcase these abilities the most are my implementation of the quicksort algorithm, display course function, and load course function. The load course function demonstrates my ability to parse in data to the program and identify the best data structures for the job that needs to be done to the data later on. I demonstrate this by implementing an unordered map for querying data with best case of O(1) time complexity and a vector for implementing efficient sorting of data with a time complexity of O(nLogn). The display course function demonstrates my ability to query data utilizing an unordered map using key value pairs. The quicksort function demonstrates my ability to correctly implement a sorting algorithm. The artifacts speed in which it can query data has been improved with the addition of an unordered map but additional space will be required to house both the vector and map data. The artifact has also been overall enhanced with the addition of exception handling to identify potential vulnerabilities and handling them without causing the program to crash.

### What I learned
Overall while completing the enhancement for this artifact I learned alot about the trade offs between utilizing different data structures and algorithms and how there is rarely ever a one size fits all solution. I have learned about the varying advantages and disadvantages of utilizing maps and vectors and how maps require work arounds for sorting data unless you utilizie an ordered map. The challenges that I had faces while improving this artifact was identifying the best possible solution for integrating both the unordered map and vector while minimizing excessive memory usage. I also learned that my original code was riddled with bugs that would occasionally cause the program to crash so implementing error handling was a massive improvement that required more time to be used.


### Course outcomes checklist
- [x] (Partially) Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
- [x] Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
- [x] Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.
- [x] Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
- [x] Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

Overall I believe this artifact demonstartes completion of the capstome course outcomes except partially for collaboration as the work originally done and ehnancements made were both done individually by myself but the code has been uploaded to github for further downloading and imporvement by others. The project does include comments and commit messages that others may take advantage of to understand the work done and how they might improve it further.

---

## Artifact 3: Databases

[**Original Artifact Repo**](https://github.com/DerekVClark/Cs340)

The third and final artifact that I have chosen to enhance and showcase in my E-Portfolio is my CS-340 finale project. For this artifact I was tasked with developing a full stack web application utilizing python, dash, and mongoDB to assist an animal shelter with storing and managing animal data currently entering, residing, and exiting their facility. For this artifacts completion I had to develop a MongoDB table for housing relevant animal information such as breed, name, age, outcome, etc... and allow for basic CRUD operations to be performed on data such as inserting a new animal record, deleting an existing animal record, updating existing records, and querying records. The original code was developed in August of 2024 and had also included visual data elements such as a pie chart and map to display animal locations. The enhanced copy takes this a step forward and integrates a google map iFrame that parameterizes a URL to display an animals information that is selected from the table. The enhanced copy also includes a doughnut and bar chart for displaying animals that qualify for becoming rescue animals in specific missions.

[**Enhanced Artifact Repo**](https://github.com/DerekVClark/Cs340/tree/enhancedWork)
### Why I have chosen this artifact
The reason why I have decided to include this artifact in my E-Portfolio is not only because of its relevance to the database category but it is also related to the career path that I have been working on going into which is full stack web development. I wanted to demonstrate my ability to completely construct both the front end for UI/UX purposes and the backend for fetching, updating, and deleting data from an external database that I have also constructed. I believe that the original artifact alongside the enhanced version shows great versatility and understanding of how to develop a database and integrate it into a visually appealing dynamic user interface. The construction of the enhanced copy which is a complete reconstruction of the original artifact utilizing the MERN tech stack instead demonstrates my great understanding of fundamental web application development principles/concepts such as routing, controllers, front end, back end, middleware, etc... along side my ability to pick up and construct working applications utilizing a variety of different tools and tech stacks. Two specific components that are apart of the enhanced copy that I believe showcase my skills and abilities in software development are the homepage for the front end and the backend animal controller. The front end showcases my aility to develop a dynamic user appealing user interface and the backend controller demonstartes my ability to safely manage succesful and unsuccesful database operations through my use of try and catch blocks. This artifact was overall improved through converting it from a python dash full stack application to a more unified javascript full stack application in which javascript is utilized both in the backend with node and the front end with react. This also included the ability for me to integrate third party libraries and packages such as react charts, react router, and even some react imports such as use state for managing a digital state, useffect hook for dynamically fetching and changing data, and reducer for developing my animal context provider.
### What I learned
Reflecting now on the process of converting my original artifact into the enhanced copy version I would say that the conversion was very trivial and time consuming due to it tasking me with completely reconstructing my code in a new language that I was not fully comfortable with. However challenging and uncomfortable this enhancement was I am very grateful for granting myself the opportunity to put myself in a position where I was forced to think outside the box and really dig deep into understanding the core concepts that make up full stack web development. In order to become more familiar with the tech stack I had to utilize many resources for express and Nodejs as I was already somewhat familiar with react for the front end. Through the process of converting my code I discovered that many of the methods for fetching, deleting, and updating at its core are the same as I had done previously just written utilizing different syntax. Once I was able to establish a deeper understanding of the coding language and the tools utilized for developing MERN full stack applications I was able to accomplish what I had set out to do with the original artifact plus more. Throughout this process I faced many challenges but I believe that if I were to further develop this application I was come into contact with many more such as if I were to implement user authentication with session tokens.


### Course outcomes checklist
- [x] Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
- [x] Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
- [x] Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.
- [x] Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
- [ ] Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

Overall I believe the enhanced artifact meets all course outcomes except for the security outcome as I was not originally planning to implement an authorization for enhanced security. I did however implement robust error handling especially when data was being transfered to and from the database and implemented data validation to only accept animal data that was valid with all data fields required fulfilled by the user.




