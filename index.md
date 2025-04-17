---
layout: default
---

<link rel="stylesheet" href="/styles.css">

# <u> E-Portfolio </u>

## Welcome
Hello my name is Derek Clark and welcome to my E-portfolio. The purpose of this E-portfolio is to not only demonstrate my ability to develop a fully fledged working application but identify weaknesses and imporvements that can be made to enhance the artifact.  Encompassed in this portfolio are three unqiue artifacts that fall under three distinct software development categories. These three distinct categories are _Software Design & Engineering_ , _Algorithms & Data Structures_ , and lastly _Databases_. 

Additionally, I have included a [**_code review video_**](#Code-Review) that was recorded prior to the enhanced works completion detailing the planned enhancement and how it will imrove the application.

In the next section of the E-portfolio I have decided to include a professional self assesment reflecting on the work I have done to complete this capstone project and my experience in the computer science program at SNHU.

## Professional Self Assesment
Completing the coursework throughout the SNHU computer science curriculum has allowed me to develop artifacts in which I can use to support my technological abilities including the use of relevant tools and practices that are commonly utilized in the software development field . Developing this E-portfolio has allowed me to take these previous works, showcase the work done, and reflect on the changes made to enhance them. Reviewing and reflecting upon past work during the construction of this E-Portfolio has granted me the opportunity to identify flaws, vulnerabilities, and weaknesses within these past works that I may have not previously been aware of. Throughout the SNHU computer science program I had the opportunity to work on many projects that involved developing solutions for real world problems both individually and as a group. Through developing these projects I have discovered many core software development principles and values such as gaining a deeper appreciation for the planning and testing phases of the software development life cycle and learning how to effectively gather user feedback to generate user-centric designs. My experience with full stack web development, databases, android development, and agile methodologies have prepared me to contribute meaningfully in various computer science related fields. 

Throughout my time at SNHU I developed projects utilizing different tech stacks and languages which allowed me to not only understand them individually but understand how to program down to the fundamentals. For example, in my data structures and algorithms course I had created various projects utilizing c++ in which I had to extract data from CSV files, insert the relevant data into the appropriate data structure, and perform operations on the data such as querying, sorting, and updating. Although this course only had us develop these projects utilizing c++ the course had given me the fundamental base knowledge of the different types of data structures, what their benefits and weaknesses are, and the understanding of time/space complexities which will benefit me in any job that involves managing data efficiently and identifying optimal computing solutions. 

On the non technical side I also developed soft skills throughout the SNHU computer science program like effective communication, teamwork, and how to properly collect user feedback. One example in which I had to collaborate with a team and communicate with stakeholders was during my enrollment in the Software Development Lifecycle course. Participating in this course meant that I would have to work with a team of peers to develop a 



## Code Review

Code reviews are an important and common practice in the field of software development allowing for a deeper more thruough look through of the code to identify possible weaknesses, vulnerabilities, and ways in which the code can be improved. The following code review video was performed by me identifying enhancements that can be made to the three artifacts included in this E-portfolio, why I have chosen the enhancements/how the enhancement will improve the artifact, and finally what are my plans for implementing the planned enhancements. The code review video demonstrates my growth as a software developer and my ability to aknowledge my own faults and improve upon them with my new found knowledge.
[![Watch the video](https://img.youtube.com/vi/MguxJ_hu0xo/0.jpg)](https://www.youtube.com/watch?v=MguxJ_hu0xo)

## Artifact 1: Software Design & Engineering
[**Original artifact repo**](https://github.com/DerekVClark/app)

The artifact that I have chosen to enhance and showcase in the category of software design and engineering is my CS-360 final project. This project originally had required me tro develop a mockup design for an inventory management application based on requirements I had gathered from mock interviews with store management personel, warehouse workers, and truck delivery drivers. The general needs of these three user types can be broken down into three core functionalities, the ability to sign in to the application using user credentials, the ability to perform CRUD functionality to inventory items (Including adding, updating, and deleting items), and recieve SMS text messages when an item in inventories quanitity is equal to zero. Following the gethering of these user requirements I was tasked with developing an adroid application utilizing the android studio IDE for constructing the user interface and communicating with an SQLite database to manage inventory items using local storage.

[**Enhanced artifact repo branch**](https://github.com/DerekVClark/app/tree/feature/barcodeScanning)

Although all user requirements were fulfilled within the scope of the original app I had identified that manual input of inventory item data was highly inefficient and users of the application may not have an easy time remembering item data like the items ID to keep track of items correctly. The solution/enhancement that I had identified through my code review is the integration of the Android devices camera allowing for users to navigate to a scan barcode page, point their camera at an items barcode, and automatically fill in item data in order to add the item to the database.

The reasoning behind my inclusion of this project in my E-Portfolio is that I believe it showcases some of my best work in the overall category of software design and engineering developing a working product with a user friendly design to solve a real world problem. The project not only demonstrates my ability to develop an android application that utilizes a database but also my ability to gather user requirements from user stories, design mockup designs, and design a unique user interface that complies with androids [best UI/UX design practices](https://developer.android.com/design/ui/mobile/guides/foundations/accessibility). I believe that overall this project demonstrates my ability to develop computing science solutions for real world problems accurately reflecting the type of work that I will be doing in the future of gathering software requirements to determine the functionality any components of the software needing to be constructed, iterating through software design diagrams for visual design/user navigation, then implementing solutions that solve user problems. A specific component included in this artifact that I believe showcases my skills and ability in software development is the barcode scanning screen. The barcode scanning screen begins by requesting camera permissions from the user demonstrating standard requirement compliance, then utilizes the camera hardware component on the android device to preview the devices back facing camera view, then the code utilizes camerax and google ML kit to obtain and analyze image frames taken from the capture to determine if a barcode exists within it. The code then takes this barcode and extracts data from it to be used for storing the item in the database. The skills and ability demonstarted by this component is my ability to integrate software with hardware, utilize external libraraies, and implement computing solutions to assist in solving user related problems. This artifact has continuously been improved allowing for the user to add items via manual data input or the use of the barcode scanning functionality along with easy navigation between pages and security measure incorporating through a login screen to safeguard user data. 

Throughout my work enhancing this artifact I have learned alot about integrating physical hadware components like the android camera into software functionality and also the exitsence of google's machine learning kit. Personally I have also learned that I am able to accomplish alot even when it comes to working with very loose guidelines and resources researching my own answers to questions I had during development and developing solutions based on the information I gathered. The challenges that I faced when implementing these enhancements was initially setting up the camera to be used in the application. Luckily I discovered the camerax library documentation which gave me a rough outline as to how to set up the camera but was not the clearest in terms of what I needed it for so I had to do some improvisation. Additionally I also had trouble integrating the image analysis functionality included in the ml kit as many of example and documentation was written in Kotlin when I was utilizing Java.

### Course outcomes checklist
- [x](Partially) Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
- [x] Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
- [x] Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.
- [x] Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
- [x](Partially) Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

Overall this artifact enhancement meets many of the capstone course outcomes except partially for security as the android application does incroporate a login page for ensuring each inventory database is locked behind a user login but the user credentials are stored locally making it easily obtainable if the device were to be iniltrated. As for the first outcome of collaboration this project was done individually by myself but the code is hosted on github with proper commit messages and comments allowing for others to download it and build upon it if desired.





## Artifact 2: Algorithms & Data Structures

## Artifact 3: Databases


