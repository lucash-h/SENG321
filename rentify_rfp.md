# Rentify

**UVic Student Rental and Roommate Matching Service**  
**Request For Proposal**  
**Version 2.0**  

---

**January 19th, 2025**  

## Document History

| Version | When       | Who      | What                 |
|---------|-----------|----------|----------------------|
| 1.0     | 2025-1-14 | Rentify  | Initial Drafting     |
| 1.1     | 2025-1-15 | Rentify  | First pass write-up  |
| 1.2     | 2025-1-18 | Rentify  | Document editing     |
| 2.0     | 2025-1-19 | Rentify  | Final revision       |

## Table of Contents
1. [Product Overview](#10-product-overview)  
2. [Project Objectives](#20-project-objectives)  
3. [Current System(s)](#30-current-systems)  
4. [Intended Users of the System](#40-intended-users-of-the-system)  
5. [Known Interactions with Systems Outside the Client Organization](#50-known-interactions-with-systems-outside-the-client-organization)  
6. [Known Constraints to Development](#60-known-constraints-to-development)  
7. [Project Schedule](#70-project-schedule)  
8. [Project Team](#80-project-team)  
9. [Reflection on the Use of AI](#90-reflection-on-the-use-of-ai)  
10. [Glossary of Terms](#100-glossary-of-terms)

---

## 1.0 Product Overview

Finding a place to rent as well as whom to rent with, is a challenge that many UVic students struggle with when trying to find a residence to live in. Discovering a rental listing that encapsulates all of the necessary specifications and desired attributes of the home often requires searching and filtering through multiple rental search websites and marketplaces. Moreover, for students who look to rent with a roommate, the process of finding potential roommates is perhaps more convoluted, as there lacks an adequate resource that recommends roommates within the same application where rental listings are posted. The hope is to optimize and improve the experience of finding rental accommodations and potential roommates by utilizing AI-powered tools to analyze individual preferences for location, price, amenities, and other factors to provide more personalized and accurate results that streamline the entire process of connecting UVic students with ideal housing and roommate options.

---

## 2.0 Project Objectives

#### 2.1 Business Objectives

##### 2.1.1 Enable students at UVic to find rental listings in a centralized application with AI
Students should be able to have a single resource that facilitates and displays all relevant rental listings across multiple rental listing platforms. AI should recommend rental listings that conform to their particular living requirements such as the number of bedrooms and bathrooms, price, and type of housing.

##### 2.1.2 Facilitate the process of matching roommates for students at UVic with AI
UVic students should be able to discover and communicate with potential roommate prospects seamlessly within a central application by recommending them to other seeking roommates. AI should internally formulate roommate matches by learning specific user preferences such as their desired location and living standards and match them with users that share similar preferences.

##### 2.1.3 The application efficiently and accurately lists scraped postings
The application should be able to successfully collect the rental listings from most relevant rental resources and display them to the users with accuracy.

##### 2.1.4 Provide a user-friendly interface for students to search/browse for listings
The application should provide an intuitive and easy-to-use interface that allows users/students to search, view, and apply for available listings in a centralized location.

#### 2.2 Success Metrics

##### 2.2.1 Enable students at UVic to find rental listings in a centralized application with AI
The application becomes the primary choice of the students moving to Victoria. 50% or more of the newcomers to Victoria use this application as their first choice when looking for accommodation.

##### 2.2.2 Facilitate the process of matching roommates for students at UVic with AI
The application is able to match users with a roommate 60% or more of the time.

##### 2.2.3 The application efficiently and accurately lists scraped postings
The showcased postings are 90% or more accurate than the original listing.

##### 2.2.4 Provide a user-friendly interface for students to search/browse for listings
Retention of new users at least at a rate of 60%. The user satisfaction in the reviews regarding the user interface is maintained at a rating of 4.2 or higher.

---

## 3.0 Current Systems

Currently, the client organization does not have an internal system specifically designed for rental listings or roommate matching. With the exception of the dedicated UVic student housing, UVic does not provide an extensive application as such. The end users rely on various third-party platforms which are not tailored to their exact needs. These platforms include but are not limited to:

#### 3.1 Roommate finding applications
Roomie, Roomster, and Spareroom are popular for roommate matching but are not designed to keep university students as a priority in mind. They lack AI-driven features and do not interact with rental listings.

#### 3.2 Accommodation finding applications
Platforms like Facebook Marketplace, Kijiji, and Craigslist are widely used for rental searches. However, these platforms are general purpose and are not specialized for student housing, making it difficult for students to find listings based on their specific needs, for example, proximity to campus.

#### 3.3 Third-party platform(s) and the current system(s) approach
The key issues with the third-party systems are fragmentation, inefficiencies, and a lack of centralization. Students must use multiple platforms to find both rental listings and potential roommates, which is time-consuming.  
Additionally, no system personalizes search results or offers roommate matching tailored to student preferences.  
The new proposed system aims to solve these problems by aggregating listings, offering AI-driven filters, and providing a centralized, student-focused platform that streamlines the search for both housing and roommates.

---

## 4.0 Intended Users of the System

The primary users of the rental website we are aiming for are students, especially UVIC or local college students, who need help finding good and affordable housing. This includes international students and local students who may or may not know the area or anyone living in the city. The rental website's solution aims to make their search easier with features like finding roommates, filters for listings, and focusing on student-friendly housing which is budget-friendly.  

Our secondary users include landlords who want to increase the publicity on their properties for students. For now, the website will be focusing more on helping students search for housing rather than letting landlords post directly.

---

## 5.0 Known Interactions with Systems Outside the Client Organization

The website is designed to interact with multiple systems that exist outside of the client organization. Those systems can be categorized into three main categories.  

The first category is multipurpose marketplaces such as Facebook marketplace, craigslist, Kijiji, etc.  

The second category is rental websites like rental.ca, rentcafe.ca, etc. Since the goal of the website is to make finding rentals easier, and putting all rentals in one place these two are very important because they will be the main source of data.  

The third category focuses on making the user experience more personalized and greater. The website will interact with applications such as Google Maps, and other map and GPS applications.  

This interaction is going to be used to ensure the renter is able to find a rental close to their preferred areas and near any specified hobbies.

---

## 6.0 Known Constraints to Development

The following constraints are important for timely updates, data accuracy, and an intuitive interface to enhance the overall user experience.

#### 6.1 Remove Listings
Users must not be able to see the listing that is removed from the original website or once rented.

#### 6.2 Status Update
The renter should be able to update the status to states such as available, or pending.

#### 6.3 Profile Privacy
The privacy of both the tenant and renter must be maintained while the user browses the listings.

#### 6.4 Localization
Supporting the multi-language interfaces and location-specific rental preferences.

#### 6.5 Timeliness of Data
Rental data needs to be up to date. Delays can lead to users interacting with expired or inaccurate listings.

#### 6.6 User Interface Complexity
Balancing comprehensive filtering options with a user-friendly design is critical, so listings are easy to browse and compare.

---

## 7.0 Project Schedule

| ID | Task                                     | Start Date | End Date   | Duration     | Assigned  | Completion |
|----|------------------------------------------|------------|------------|--------------|----------|------------|
| 1  | Release request for proposal to market   | 2025-01-12 | 2025-01-19 | 1 Week       | Rentify  | 100%       |
| 2  | Requirements Document 1.0 (vision & scope) | 2025-01-19 | 2025-02-02 | 2 Weeks      | Developers | 0%       |
| 3  | Requirements Document 1.1 (client gives feedback) | 2025-02-02 | 2025-02-04 | 2 Days       | Rentify  | 0%         |
| 4  | Requirements Document 2.0 (data models & user stories) | 2025-02-04 | 2025-02-16 | 1 Week 5 Days | Developers | 0%  |
| 5  | Requirements Document 2.1                | 2025-02-16 | 2025-03-09 | 3 Weeks      | Developers | 0%        |
| 6  | Prototype Demonstration                  | 2025-03-12 | 2025-03-12 | 1 Day        | Developers | 0%        |
| 7  | Prototype Feedback                       | 2025-03-12 | 2025-03-12 | 1 Day        | Rentify   | 0%         |
| 8  | Requirements Document 3.0 (incorporate all client feedback) | 2025-03-12 | 2025-03-30 | 2 Weeks 4 Days | Developers | 0% |
| 9  | Final Prototype Demo                     | 2025-04-01 | 2025-04-03 | 3 Days       | Developers | 0%        |

---

## 8.0 Project Team

Rentify Company consists of nine motivated individuals who can be contacted at the following email addresses:

- **Dave Jung** - davejinyoung@uvic.ca - Writer (section 1 & 2), Editor  
- **Kevin Jin** - kevinjinubc@gmail.com - Writer (section 9)  
- **Sam Addison** - 2samaddison@gmail.com - Writer (section 9), Editor  
- **Shounit Kamboj** - shoun7777@gmail.com - Writer, Editor  
- **Varun Saini** - varunsaini@uvic.ca - Writer (section 6)  
- **Taqdeer Kaur Sandhu** - taqdeer.san@gmail.com - Writer (section 3), Editor  
- **Sunpreet Singh** - sunpreetsingh1@uvic.ca - Writer, Editor  
- **Samuel Jones** - samuelahjones@uvic.ca - Writer, Editor  
- **Grygorii Karachevtsev** - gregory.karachevtsev@gmail.com - Writer (sections 1, 2, 9), Editor  

---

## 9.0 Reflection on the Use of AI

1. **List all the ways that your team used generative AI in this deliverable. Please be specific. (E.g. to identify key stakeholders).**  
   - AI was used to help identify some of the key stakeholders in this project  
   - AI was used to help identify important terms to use in the Glossary<br><br>
2. **Which AI model(s) did you use? (E.g. ChatGPT 4o)**  
   - We used ChatGPT 4o and o1 models.<br><br>
3. **What similarities and differences did you notice between your content and the content generated by AI? Please give examples from your RFP.**  
   - The AI-generated RFP and our team’s RFP share common goals, such as centralizing rental listings and offering roommate matching for UVic students. However, the AI’s version is more high-level, while our RFP provides specific success metrics and clearer details on how AI should match roommates based on user preferences. The AI also focused on general goals, while we included measurable targets like user retention and listing accuracy.  <br><br>
4. **What aspects of the AI-generated artifact surprised you or that you hadn't considered? Provide examples from your RFP.**  
   - The AI’s emphasis on engagement metrics, such as session duration and interactions with AI-powered features, was surprising as we hadn’t considered these in detail. Additionally, the suggestion to integrate payment systems was unexpected but might be useful for future iterations.<br><br>
5. **What are some areas where AI did not help you in writing your RFP? Be specific about those areas.**  
   - Sometimes, AI provided excessive information that we thought would overcomplicate our scope and project rather than help it. For example, when listing the end users, AI included tertiary users such as service providers (Cleaning/moving companies) for information on advertising to new renters. This was much too far beyond our envisioned scope so we decided to disregard it.<br><br>
6. **What did you do when AI’s content differed from your own content? How did you decide what content to keep? Give examples of the differences here.**  
   - When the AI’s content didn’t align with ours, we focused on our more specific approach, especially regarding AI features and success metrics. For instance, the AI was unclear about how roommate matching should function, so we included our detailed description of matching based on preferences like location and living standards.<br><br>
7. **How confident were you in generative AI’s output?**  
   - We felt confident in the AI’s ability to provide structured content and generate general goals, but less confident when it came to details like AI features or success metrics. The AI’s high-level approach required further refinement to meet our specific needs.<br><br>
8. **In your observations, what made prompts effective, and what made prompts ineffective? How did you decide that a prompt was effective, or not? Please give examples of your prompts for both good and bad prompts and your perceived good and bad responses from the AI model.**  
   - Effective prompts were specific, like asking for measurable success metrics for AI features. Ineffective prompts, such as “Describe the platform’s features,” led to vague responses. Clearer instructions helped the AI focus on providing more detailed, actionable content. <br><br>
   **Bad prompt example - section 5**  
   _“We are a client org writing a rfp. the RFP is for a website that integrates AI and looks through multiple different websites like fb marketplace, craigslist, and rental websites. The goal of our website is to make student rental search easier, and all in one place. in the RFP, we want to list known Interactions with Systems Outside the Client Organization”_  <br><br>
   When given the above prompt to ChatGPT, it resulted in irrelevant suggestions, such as payment systems and machine learning algorithms, which were outside the scope of our project. It also went unnecessarily deep into technical details, causing confusion. To get a more focused response, we should clearly instruct GPT to provide only the information we need, avoiding unrelated or excessive details.<br><br>
   **Good prompt example - section 1:**  
   _“We are developing a Request for proposal for a website/project that has been drafted as follows:  
   Hard to find places to live near campus and hard to find roommates if you’re moving here alone.  
   Use AI to cross-search to find and collect rental options  
   Input rental ideal preferences. Wants and don’t wants  
   Roommate finder (Maybe?)  
   Have APIs and Be able to post things yourself.  
   Put in tags on your personal profile to help find roommates you might like.  
   AI (Recommender System)  
   AI learns from the rentals and roommates you’re interested / not interested in and updates your internal preferences as such  
   Social media post capabilities (Maybe?)  
   We need to develop a Product Overview section that clearly and thoroughly outlines the product and its objectives. To help with the task, here is a sample project objective section you can use as an example:  
   At Black Lung Mining Co. we want to optimize our mining operations by retrieving data about our haul truck operations. Currently, we are facing a number of problems:  
   Wait times at shovels are not evenly distributed causing severe delays for some drivers  
   These delays may in part be attributed to slow drivers  
   There is no way to track load time, driver break time or 360 inspections  
   There is no real-time location tracking for trucks  
   Rerouting is done verbally instead of on a detailed map on a screen  
   Dangerous drivers are causing accidents on our site  
   We hope to use the data retrieved to reroute trucks, identify slow and fast trucks and drivers, minimize wear on engines, minimize idle time, and minimize travel to load ratio to generally improve the efficiency of our on-site hauling operations.”_  <br><br>
   This prompt contained the initial project idea and provided an example of a project objectives section, thereby giving ChatGPT enough information to construct a well-structured project objectives section. Overall, the material that was generated was similar to our written project section.<br><br>
9. **If you had to repeatedly prompt the AI model, why did you keep updating your prompt? What changes were you making to your prompts? How did you know when you were satisfied with the output? Give examples of conversations requiring repeated or changing prompts.**  
   We updated our prompts to refine the AI’s output, especially when it was too general. For example, we clarified the need for roommate matching to be based on specific criteria. We were satisfied when the responses were detailed and aligned with our project’s goals.<br><br>
10. **Did you perceive that the AI model gained and maintained contextual understanding during the conversation? E.g. did you keep having to remind the model of something introduced early on? What context did it remember and what context did it forget?**  
    The AI maintained context well for the core elements, like UVic students and centralizing listings. However, it occasionally needed reminders for more specific details. Sometimes AI would forget about the concepts we mentioned earlier.

---

## 10.0 Glossary of Terms

**AI (Artificial Intelligence)**  
Technology that enables computers and machines to simulate human learning, comprehension, problem-solving, decision-making, creativity, and autonomy  

**Centralized Application**  
A single platform that combines rental listings and roommate-matching features for students.

**Rental Listing Aggregation**  
Collecting rental postings from various websites into one place for easy access.

**Roommate Matching**  
A feature that helps students find suitable roommates based on shared living preferences.

**Real-Time Updates**  
Synchronizing with external websites to keep rental listings current and accurate.

**User-friendly interface**  
A software interface that is easy to use and navigate. It's designed to be intuitive so that users can accomplish their tasks with minimal effort.