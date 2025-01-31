You may use this requirements document template to get your requirements document started for your designer team.

# Requirements Document - Project Name (date created)

# Revision History

| Name            | Date       | Reason for Changes                                  | Version |
| --------------- | ---------- | --------------------------------------------------- | ------- |
| Parker DeBruyne | 2025-01-27 | Initialized document, added framework for 2.0 - 4.1 | 1.0     |
|                 |            |                                                     |         |
|                 |            |                                                     |         |
|                 |            |                                                     |         |

0. **Table Of Contents**

   2. Business Requirements
      1. Background
      2. Business Opportunity
      3. Business Objectives
      4. Success Metrics
      5. Product Vision Statement
   3. Scope and Limitations
      1. Major Features
      2. Project Scope
      3. Limitations and Exclusions
   4. Context Description
      1. User Classes and Characteristics
      2. Operating Environment
      3. Design and Implementation Constraints
      4. Assumptions and Dependencies
      5. Glossary of Terms
      6. References
   5. System Features
      1. System Feature 1
         a. Description and Priority
         b. Functional Requirements
         c. Use cases associated with the feature or functional requirement
      2. System Feature 2
         a. ...
         b. ...
         c. ...
   6. Data Requirements
      1. Logical Data Model
      2. Data Dictionary
      3. Reports
      4. Data Acquisition, Integrity, Retention, and Disposal
   7. External Interface Requirements
      1. User Interfaces
      2. Hardware Interfaces
      3. Software Interfaces
      4. Communication Interfaces
   8. Software Quality Attributes
      1. Usability
      2. Performance
      3. Security
      4. Safety
      5. Reusability
      6. Maintainability
      7. Availability
      8. Interoperability
   9. Analysis Models
      1. Data Flow Diagrams
      2. Sequence Diagram
      3. Storyboard
      4. Swimlane Diagram
   10. Appendix

1. **Overview**

   1. **Purpose**
      This requirement document (RD) describes the functional and non-functional requirements of the UVic Student Rental and Roommate Matching Service (Rentify). The document is intended to be used by the members of the software development team who will implement and verify the correct functioning of the system. The document is also available to other stakeholders such as clients for use as a reference during the development progress.
   2. **Project Scope**
      Rentify assists students studying from the University of Victoria (UVic) in finding suitable rental spots and roommates, using gathered data from various rental listing websites that focus on Victoria, British Columbia where the university is located. A detailed description of the concept is available in the document Request for Proposal: UVic Student Rental and Roommate Matching Service [citation #].

1. **Business Requirements**

   1. **Background**

      The rental market currently thrives off of websites like facebook marketplace, kijiji and craigslist, allowing renters to browse and contact listings while allowing landlords easy advertising for their property. Websites like Roomies, Roomster or social media apps can help find roommates from people you have met or have yet to meet. However, finding yourself ready to move into a new city, especially from out of country even with these resources is a daunting task and raises plenty of questions:

      - Are these listings reliable?
      - I can’t afford a single bedroom place, how can I meet others to rent a cheaper property with more bedrooms?
      - How can I ensure that my future roommates are respectful and have similar values to myself?
      - Is it better to be searching on facebook, kijiji, craigslist or a different website?
      - Can I use any of these applications if I don’t speak English?
      - Am I using the right resources that give me the greatest choice and selection for rooms and roommates?

      Realizing that these issues are very real, especially in a city like Victoria, our clients developed the idea of Rentify that provides an easy solution to the issues outlined above, while effectively creating a new market for itself that complements pre-existing solutions, rather than replacing them.

   2. **Business Opportunity**

      In the current housing market, there are many apps and websites that help people find and advertise rental listings; some are Facebook Marketplace, Craigslist and Kijiji. There are also several options for finding roommates including roomie, roomster or facebook groups. However, none of these options are sufficiently integrated with each other to make the process of finding roommates and rooms for rent easy. Rentify is proposing a web app of the same name that gathers all the existing rental listings from the web, and provides a platform for renters-to-be to communicate and send listings to each other, greatly facilitating the search for a place to live. It could be argued that Facebook fulfills this role with Facebook Marketplace and Facebook groups, but there is a large enough amount of rental listings and roommate finders that are not found on Facebook to justify Rentify’s goal of creating this product. Gathering all the needed information in a single platform will increase the ease of finding individual or group rentals, especially for international or non-english speaking persons.

      The Rentify platform will provide a language functionality that allows a user to interact with the website in a number of languages, including English, French, Mandarin, Japanese and Korean. Moreover, this solution does not replace platforms such as Facebook, Kjiji. Instead, Rentify complements them by utilizing their listings and allowing renters to easily meet and communicate while the renter-landlord conversation still occurs through the current platforms. This means Rentify will not need to squeeze into the current rental market but rather adds to it, effectively creating its own market.

      In the past, an international student would have to navigate room and roommate finders that they may not be familiar with in a language they don’t know or rely on their institution to assist them with setting up housing. Institutions can be difficult to deal with, and Rentify would provide this student with a platform that gathers all their needed information on one platform, allowing them to meet people and browse listings in their language.

      This product would also be an attractive option as a local user with a lay of the land. No matter who you are, keeping track and browsing multiple websites for many different room posts is quite a chore. Using Rentify, this user can find all these posts on one platform, and if needed they can find roommates with similar interests to them.

   3. **Business Objectives**
      
      At the moment, the rental market is divided between other services such as facebook marketplace, kijiji and craigslist. There is also the issue of trying to find compatible roommates. Rentify aims to provide an easy to use interface that makes it easy to find rentals or roommates, and communicate with potential roommates. The business objectives can be summarized as shown below.

   a. Rentify aims to have 50% of successful student rentals in Victoria through the platform. 

   There are approximately 23,000 students that return to the University of Victoria in the fall and on campus accommodation can only host 2300 students. Based on these statistics, and taking other factors into consideration, such as students that already have housing and students who commute from home the number of incoming students per semester is around 4500.. Approximately half of these students move into on campus housing. Given these figures, a strong business objective is to have 50% of the students moving into off-campus housing find their rentals through Rentify.

   b. Successfully match roommates that are compatible with each other. 
   
   This is measured by the percentage of matched roommates carrying out their predefined living arrangement to completion. We expect to achieve a “roommate satisfaction rate” of 60% which can be improved over time by refining the algorithm. This can be achieved by ensuring the accuracy of the roommate matching algorithm which leverages machine learning to factor in compatibility metrics such as cleanliness, noise tolerance, study habits and so forth.
   
   c. Monetization: Rentify has a few different methods it can use to generate revenue.
   
   - Using targeted advertisement from landlords, property management companies and any other interested parties. 
   - User data is collected and aggregated in such a way as to get valuable insight into rental trends which can be used to provide market data to other companies in the real estate industry.
   - The same data that was collected can also be used to build datasets relating to statistics relevant to real estate. This data can then be used to train ML models which can be used for various industry purposes.


   4. **Success Metrics**
      a. 60% of new users should successfully find rentals through Rentify. This means that 60% of all the user traffic that passes through the website must end in the user finding a rental. This can be measured by: And it can be affected by factors such as: availability of rentals, and number of users. The longer 
   
   b. 90% of the rental listing in the city must be accessible through our website. This is essentially a metric of how well the web scraper accomplishes its purpose. With time, the scaping algorithm can be improved to avoid repeated listings (getting the same listing from multiple sources).
   
   c. The average use review score must be greater than 4.2. 
   - The key to achieving a positive user review will be to ensure a positive experience searching for a rental/roommate. Rentify consolidates all of the online rental listings in Victoria into one platform and makes it easier to search. 
   - Another key factor is going to be matching roommates successfully. The search engine will be highly advanced making use of large language models to successfully match compatible roommates. 



   5. **Product Vision Statement**

      For any renter but with a focus on students who are looking for a room, roommates and are unfamiliar with the area and/or language. Rentify is a web application that congregates rental listings from the internet and allows potential renters to find like minded roommates while minimizing language barrier issues. Unlike Kijiji, Facebook, Craigslist or Roomies, Rentify provides a platform that allows the user to search listings from any of the aforementioned websites, share those listings with others, and find roommates that share their interests.

![Screenshot 2025-01-30 215420](https://github.com/user-attachments/assets/db29a40c-b13e-41d1-89ae-f357ef629ce5)
The figures above show a simple depiction of how the Rentify web app would fit into the rental/roommmate finder software ecosystem. The first figure shows a user dealing with six different, commonly used rental and roommate finding websites. The second simply shows how Rentify would centralize the data, providing a much simpler task for the user.

3. **Scope and Limitations**

   1. **Major Features**

   Create Personal Account
   The first thing a user will do is create a personal account. Here they will input information about personal information about themselves including traits, age, gender, hobbies, occupation, living style and more. This information will later be used in the roommate matching feature. There will be a set of selections that users pick, in order to later filter roommates for quick search. Users will also create a custom hand written bio about themselves, which will use AI for more specialized roommate matching and searching.

   Roommate Matching
   This feature will find users potential roommates based on shared preferences and compatibility. Users can search by name to find specific individuals or apply filters that align with their selected traits, such as age, gender, student status, political views, hobbies, smoking habits, noise tolerance, and cleanliness preferences. For a more personalized experience, an AI-powered search analyzes users’ custom-written bios to identify deeper compatibility beyond preset filters. Once the search results generate a list of potential roommate matches, users can review profiles and send requests to start a conversation, making it easier to find the perfect living companion.

   Request to message
   This function is in place to control incoming messages; to give the user choice of who they will accept messages from. Anyone can request to message another user, but the receipient must accept the request in order for the conversation to continue. Additionally, the app supports group chat functionality, enabling multiple users to interact, which is ideal for discussing living arrangements. Here they can also share rental listings which they might hope to live in together.

   Search Housing
   The user will prompted to input their preferrences of a living space from a set of options. These options would include price, number of rooms, number of bathrooms, green space, balcony, type of rental, garage, neighborhood. Then the app will retrieve all similar listings and present them to the user in a efficient set up where they can easily view the potential matches. If a user likes a place, they can see more info and the app will also provide the link to the listing, where they can apply for it. There will be a feature where users can share listings with other users via messaging.

   2. **Project Scope**

   The purpose of Rentify is to simplify the renters housing search process. It will give them an efficient way to search all listings across all sources of an area. It will give student renters an effective way find compatible roommates and streamline the search. Benefits for the students include accelerated search process, improved roommate living situations, built-in AI translator for communication. Benefits for landlords will provide them with better tenants, and give them more options of tenants. Some objectives include customer satisfaction, popularity among student rentals, and success in scraping and compiling all the available listings.

   Rentify is not a profit driven company but does hope to be net positive in terms of costs and revenue. Rentify hopes to ethically sell unanimous data to marketing firms, and also gain profit from internal targeted advertising. Rentify hopes to have positive user satisfaction and become a common platform among student renters.

   3. **Limitations and Exclusions**

      1. **Exclusions**

      In order to keep the scope of the project realistic we had to make some limitations and exclusions. We focused the scope on functionality rather than features, and will consider some of these secondary features later once the app is profitable. Some of the features we had to exclude:

      - User search history
      - Tinder style swipe for matching Roommates
      - User set status
      - Multi Language interfaces
      - Landlords interface
      - Helpdesk / user tech support
      - Data validation: Live / direct database API integration with other listing websites
        - (we're just relying on web scraping and providing redirect links for now, like a "cheapest-flight finder")

      2. **Limitations**

      Search Bar Limitations
      The search functions will have limited capabilities. For the main search functionality there will be a set of clickable options which filters the searches, rather than implement an AI search. Similar to taking a survey, you will input your preferences from a set of options. This will apply for the functionality of both roommate search and rentals search. We will however implement AI search function for reading and searching personal bio's, this function will be done locally to prevent data leaks and increase efficiency.

      Rental Application Limitations
      Instead of offering direct rental application and landlords connections, we have chosen to instead offer the link where the rental was found. We chose the path to limit the sharing of private info, as well as the former would be difficult to implement due to varying rental application proccess.

      Roommate Matching
      The roommate matching will be done on a match most similiar hierarchy, and then display the users differences to each other. This will increase the number of potential matches, thus, increasing the chances of finding a roommate.

      Priority Features
      We hope to later add more AI features including an AI assistant to help with the search process, and to help customize your profile. Another priority feature is Multi Language capabilities. This will greatly benefit international students who are using the app. These features are not in the scope of the first release, but will be the first to be implemented in a later release of the app.

4. **Context Description**

   This section outlines the important factors that will affect the design and development of Rentify. It describes the different types of users, technical environment, and any limitations or dependencies that may impact the system. Understanding these factors is crucial to ensure that the system is designed to meet the needs of the user, while remaining compatible with other systems, requirements, and technical constraints. The following sections cover user roles, operating environment, and design constraints that need to be considered.

   1. **User Classes and Characteristics** <br>
      NOTE: **Need feeback from team to decide if we want to have technical admins or developers as a user class, or if we need any other user classes.**

      Identify the various user classes that you anticipate will use this product. User classes may be differentiated based on frequency of use, subset of product functions used, technical expertise, security or privilege levels, educational level, or experience. Describe the characteristics of each user class. Certain requirements may pertain only to certain user classes. Distinguish the favored user classes from those who are less important to satisfy.

      - Highest priority: Student Renters
      - High priority: International Student Renters
      - Medium priority: Landlords
      - Low: System maintenance workers & IT

      | User Class                                 | Description                                                                                                                                                                                                                                                                                                                                                                                                          |
      | ------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
      | **Renters**                                | An individual seeking rental accommodations in Victoria BC, Canada. They will use the rental finder section on the Rentify app to browse rental listings and apply filters (e.g. price, location, amenities, etc.) to find a suitable place. Once they find a listing of interest, the user will click a button that redirects them to the original posting where the user can proceed with the application process. |
      | **Roommate-seeker**                        | An individual seeking roommates in Victoria BC, Canada. They will use the roommate-finder section on the Rentify app to find potential roommates, by applying filters, browsing profiles, and requesting to send a message to a suitable match.                                                                                                                                                                      |
      | **Admins**                                 | A group responsible for managing and maintaining the Rentify app. Admins oversee system operations, platform stability, and community guidelines. Admins have access to backend tools for user account management, listing management, and data monitoring.                                                                                                                                                          |
      | **Maybe?: Technical admins or developers** | Fix bugs and those kinds of things (more will be added here if we want this user class)                                                                                                                                                                                                                                                                                                                              |

   2. **Operating Environment**

      Describe the environment in which the software will operate, including the hardware platform, operating system and versions, and any other software components or applications with which it must peacefully coexist.

      Our choices for the tech-stack are based on simplicity and low cost. The software will be hosted on **DigitalOcean Droplet[#]** for its ease of use and low fixed-pricing tier of $4/m for small startups. The relational database will be written in **postgreSQL [#]** since it's open source and free. Our chosen LLM is **Llama AI [#]** by Meta for its easy API integration. Our middle-ware framework will be **Node.js [#]** as it is highly compatible with our front-end framework; **React [#]** and **React Native [#]** for web and mobile users respectively. React and ReactNative are popular frameworks with many supporting libraries and easily hireable labour for maintenance staff.

      In a summary list, the tech-stack of our operating environment is as follows:

      1. **DigitalOcean Droplet[#]**
      2. **postgreSQL [#]**
      3. **Llama AI [#]**
      4. **Node.js [#]**
      5. **React [#]**
      6. **React Native [#]**

   3. **Design and Implmentation Constraints**

      Describe any items or issues that will limit the options available to the developers. These might include: corporate or regulatory policies; hardware limitations (timing requirements, memory requirements); interfaces to other applications; specific technologies, tools, and databases to be used; parallel operations; language requirements; communications protocols; security considerations; design conventions or programming standards (for example, if the customer’s organization will be responsible for maintaining the delivered software).

      NOTE: **I (Shaban) will most likely add more here, any suggestions welcome**

      | **Technical Constraints**             | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
      | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
      | **Platform Compatibility**            | The system must be accessible through web browsers and mobile apps (iOS and Android), requiring cross-platform development.<br><br>**Potential Issues:**<br>• UI may differ between platforms requiring separate optimizations.<br>• Performance issues can arise on lower-end mobile devices.                                                                                                                                                                                                                                                                                             |
      | **API and Data Scraping Limitations** | Third-party rental platforms may limit API access or not have an API at all, leaving Rentify to scrape all the data.<br><br>**Potential Issues:**<br>• If no API is available, Rentify must scrape the website, which can be legally restricted.<br>• Some websites block automated scraping.<br>• Web scraping isn’t as effective in providing real-time data as APIs.<br>• If too many requests have been made, Rentify may hit rate limits preventing new listings from being updated.<br>• API costs may increase if a provider charges for each/extra request, impacting scalability. |
      | **Performance Limitations**           | When users browse and apply filters, Rentify should process these results instantly.<br><br>**Potential Issues:**<br>• Large datasets can slow down filtering results if queries are inefficient or if indexes are inefficient.                                                                                                                                                                                                                                                                                                                                                            |
      | **Real-Time Data Updates**            | Rentify must constantly add new listings to the app.<br><br>**Potential Issues:**<br>• If updates run too frequently, the server load can increase causing slowed-down user interactions.<br>• If updates aren’t run frequently enough, outdated listings may be added.                                                                                                                                                                                                                                                                                                                    |

   4. **Assumptions and Dependencies**

      List any assumed factors (as opposed to known facts) that could affect the requirements stated in the RD. These could include third-party or commercial components that you plan to use, issues around the development or operating environment, or constraints. The project could be affected if these assumptions are incorrect, are not shared, or change. Also identify any dependencies the project has on external factors, such as software components that you intend to reuse from another project.

      The core assumption of our software is that rental listing data can be reliably scraped from the largest source, **Facebook Marketplace**. While theoretically possible, much of our software’s utility depends on this functionality, and so the discernment of this possibility is our highest priority.

      Our second assumption is not only that an **MLM** can reliably match rental users into compatible groups based on profile tags, but that groups of similar people are in fact more compatible—it may be that “identical interests” are not as stable as “diverse interests” when it comes to roommate groups.

      Our final assumption is that **student renters** would prefer to aggregate searches from many platforms into one place as opposed to simply using their current largest source: Facebook.

      Our software depends on three main assumptions that are best phrased as questions:

      1. **Can we successfully scrape listing data from Facebook Marketplace?**

      2. **Can an MLM be easily implemented to match people into stable groups?**

      3. **What does modern Sociology and Psychology say about team cohesion and personality characteristics?**

   5. **Glossary of Terms**

      Define all the terms necessary to properly interpret the RD, including acronyms and abbreviations.

      i. **API**

      1. Application Program Interface
         - A set of rules and protocals that allow different softwares to interact with each other. Often used to send or receive data between services.

      ii. **Tech-stack**

      1. Collection of technologies used to build and run a website or application.

      iii. **MLM**

      1. Machine Learning Model
         - An AI driven system that learns from data to improve recommendations or predictions.

      iv. **LLM**

      1. Large Language Model
         - A type of AI trained to on datasets to understand how to generate human-like text.

      v. **Data/Web Scraping**

      1. Automated process used to extract data from websites by parsing HTML. Used when API is not available.

      vi. **Cross Platform Development**

      1. Process of building software that can run on multiple operating systems.

      vii. **Rate Limit**

      1. A restriction imposed by APIs that limit the number of requests that can be sent.

      viii. **Communication Interface**

      1. The ways that Rentify interacts with external systems.

      ix. **Data Acquisition**

      1. The process of gathering rental listing data from various sources.

      x. **Data Integrity**

      1. Ensuring that rental listings and user data remain accurate and unchanged during processing and storage.

      xi. **Indexing**

      1. A database optimization technique used to speed up searching and filtering large sets of data.

   6. **References**

   List any other documents or Web addresses to which this RD refers. These may include user interface style guides, contracts, standards, system requirements specifications or use case documents. Provide enough information so that the reader could access a copy of each reference, including title, author, version number, date, and source or location.

- **Class textbook**

  - [#] K. Wiegers and J. Beatty, _Software Requirements_, 3rd ed. Redmond, WA, USA: Microsoft Press, 2013.

- **React Native**

  - [#] React Native Documentation, React Native, Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://reactnative.dev/docs/getting-started](https://reactnative.dev/docs/getting-started)

- **PostgreSQL**

  - [#] PostgreSQL Documentation, PostgreSQL Global Development Group, Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://www.postgresql.org/docs/](https://www.postgresql.org/docs/)

- **Node.js**

  - [#] Node.js Documentation, OpenJS Foundation, Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://nodejs.org/en/docs/](https://nodejs.org/en/docs/)

- **DigitalOcean**

  - [#] DigitalOcean Documentation, DigitalOcean, Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://docs.digitalocean.com/](https://docs.digitalocean.com/)

- **Llama LLM**

  - [#] Llama Documentation, Meta AI, Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://ai.meta.com/llama/](https://ai.meta.com/llama/)

- **Lucidchart ER Diagrams**

  - [#] Lucidchart, "How to Draw an ER Diagram," Lucid Software Inc., Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://www.lucidchart.com/pages/how-to-draw-ERD](https://www.lucidchart.com/pages/how-to-draw-ERD)

- **Figma UI Prototyping**

  - [#] Figma, "Figma: The Collaborative Interface Design Tool," Figma, Inc., Accessed: Jan. 28, 2025. [Online]. Available:  
    [https://figma.com](https://figma.com)

- **Apify**
  - [#] Apify, "Web scraping and automation platform," [Online]. Available:  
    [https://apify.com](https://apify.com). Accessed: Jan. 29, 2025.

6. **System Features** (Due Iteration 2 and beyond)

   This template illustrates organizing the functional requirements for the product by system features, the major services provided by the product. You may prefer to organize this section by use case, mode of operation, user class, object class, functional hierarchy, or combinations of these, whatever makes the most logical sense for your product.

   Functionality Overview - Scrapes multiple housing rental sites and compiles all the information - inputs data to local database, to improve the speed of the search - filters through preset filters to customize search - Web Scraping - local database with all the listings, refreshed periodically, to make faster searching, better AI functinality - Maybe use AI to handle reading the ad writeups, and extracting the data to input into our database

   1. **System Feature 1**

      State the feature name in just a few words.

      1. **Description and Priority**

      Provide a short description of the feature and indicate whether it is high, medium, or low priority.

      - Highest: roommate matching
      - High: listing search & redirect
      - Medium: Landlord listing posting
      - Low: multilanguage translation

      2. **Functional Requirements**

      Where applicable - Itemize the detailed functional requirements associated with this feature. These are the software capabilities that must be present in order for the user to carry out the services provided by the feature, or to execute related use case(s). Include how the product should respond to anticipated error conditions or invalid inputs. Requirements should be concise, complete, unambiguous, verifiable, and necessary. Use “TBD” as a placeholder to indicate when necessary information is not yet available.
      Each requirement should be uniquely identified with a sequence number or a meaningful tag of some kind. These could be requirements that the clients provided directly or were defined by the designer group as a result of rendering the feature.
      Each requirement should also include information a(1) bout Backward Traceability (the rationale for the requirements and the source – RFP and which section in it, client meeting and which notes from that meeting, etc.. and (2) Forward Traceability (how the requirement can be verified by the users.

      REQ-1:

      REQ-2:

      3. **Use cases associated with the feature or functional requirement**

         This is the use case specification. For each Use Case, list the dialog elements in the use case that elaborates or is related to this feature or one of its functional requirements, i.e. sequences of user actions and system responses that stimulate the behavior defined for this feature/functional requirement.

   2. **System Feature 2 (and so on)**

7. **Data Requirements**
   1. Logical data model
      E.g., entity-relationship diagrams and UML class diagrams. You may provide a data model for the business operations or the data that the system modifies. Not the same thing as a database design data model.
   2. Data dictionary
      Composition of data strucutres, meaning, data type, length, format, and allowed values.
   3. Reports
      If your system will generate reports, then describe the attributes of those reports. You can detail the layout of the report.
   4. Data acquisition, integrity, retention, and diposal
      If possible, describe how data is acquired, retained, and later on disposed. Describe the requirements for protecting the integrity of the data.
8. **External Interface Requirements**

   1. User Interfaces

      Describe the logical characteristics of each interface between the software product and the users. This may include sample screen images, any GUI standards or product family style guides that are to be followed, screen layout constraints, standard buttons and functions (e.g., help) that will appear on every screen, keyboard shortcuts, error message display standards, and so on. Define the software components for which a user interface is needed.

   2. Hardware Interfaces

      Describe the logical and physical characteristics of each interface between the software product and the hardware components of the system. This may include the supported device types, the nature of the data and control interactions between the software and the hardware, and communication protocols to be used.

   3. Software Interfaces

      Describe the connections between this product and other specific software components (name and version), including databases, operating systems, tools, libraries, and integrated commercial components. Identify the data items or messages coming into the system and going out and describe the purpose of each. Describe the services needed and the nature of communications. Identify data that will be shared across software components.

      - Data scraping:
        - Google Play Scraper: https://github.com/JoMingyu/
        - google-play-scraper
        - Reddit Access: https://pushshift.io/signup
        - Stackexchange: https://archive.org/download/
        - stackexchange
        - Stackexchange data explorer: https://data.stackexchange.com/stackoverflow/query/new

   4. Communication Interfaces

      Describe the requirements associated with any communications functions required by this product, including e-mail, web browser, network server communications protocols, electronic forms, and so on.

9. **Software Quality Attributes**

   Specify requirements that include performance, security, reusability, maintainability, usability, availability, interoperability, etc.

10. **Analysis Models (Data Flow Diagrams, Sequence Diagram, Storyboard, Swimlane diagram)**

- 1 level 0 data flow diagram
- 1 level 1 data flow diagram
- at least 2 level 2 data flow diagrams
- at least 2 dialog maps
- storyboard for features/functional requirements
- system level sequence diagram for each use case
- 1 swimlane diagram for each use case

10. **Appendix**
