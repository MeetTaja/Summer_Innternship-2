# summerintership2024_21IT160

# 🌟 Web Development Summer Internship 2024 🌟

Welcome to my GitHub repository for the Web Development Summer Internship 2024! This project showcases the work done during the internship, including practical insights and hands-on experience. 

# Start of Internship

## 1️⃣ week 1
### *27th May 2024*
- The first week of the internship involved an introduction to the company’s web development practices, familiarization with the tech stack, and initiation into the ongoing projects. The main focus was on understanding the project requirements, setting up the development environment, and beginning work on assigned tasks.


### *Here is the Outine of Week-1:*

1. Introduction to the company's web development practices.
2. Familiarization with the tech stack.
3. Initiation into ongoing projects.
4. Focus on understanding project requirements.
5. Setting up the development environment.
6. Beginning work on assigned tasks.

## 📝 Day-by-Day Progress

### Day 1: Orientation and Onboarding
- Attended the orientation session to learn about the company’s mission, values, and culture.
- Set up company email and communication tools (e.g., Slack, MicrosoftTeams).

### Day 2: Development Environment Setup

- Installed and configured the required development tools (e.g., Visual Studio Code, Git, Node.js).
- Cloned the project repositories from the company's GitHub/GitLab.
- Set up local development environment, including running the development server and understanding the project structure.

### Day 3: Understanding the Tech Stack

- Studied the technologies used in the project (e.g., HTML, CSS, JavaScript, React, Node.js).
- Reviewed the documentation and codebase to understand the architecture and design patterns.

### Day 4: Initial Project Involvement

- Participated in project meetings to understand current objectives and deliverables.
- Started working on a beginner-friendly feature/bug fix as a first task.
- Collaborated with team members to understand the workflow and code review process.

### Day 5: Learning and Development
- Engaged in self-learning sessions on specific technologies and tools used in the project.
- Completed online tutorials/courses recommended by the team lead.

## 2️⃣ week 2

### *3th June 2024*
- In the second week, the primary focus was on the development of a personal portfolio website. This involved designing the layout, implementing core features, and ensuring responsive design. Collaboration with the design team and feedback from mentors were integral parts of this process.


### *Here is the Outine of Week-2:*
1. Focus: Development of a personal portfolio website.
2. Activities: Designing layout, implementing core features, and ensuring responsive design.
3. Collaboration: Worked with the design team and received feedback from mentors.

## 📝 Day-by-Day Progress

### Day 1: Layout Design

- Collaborated with the design team to finalize the website’s layout and visual elements.
- Created wireframes and mockups using design tools such as Figma or Adobe XD.
- Integrated feedback from mentors to refine the design.

### Day 2: Development of Core Features

- Implemented the home page, about me section, and portfolio section using HTML, CSS, and JavaScript.
- Developed reusable components (e.g., header, footer, navigation bar) to maintain consistency across pages.
- Ensured cross-browser compatibility and adherence to web standards.

### Day 3: Responsive Design

- Applied responsive design principles to ensure the website is mobile-friendly.
- Used CSS media queries to adapt the layout for different screen sizes.
- Tested the website on various devices and browsers to ensure a seamless user experience.
   
### In Day 4-5 i was supposed to explore and learn new services in brief by my own

### Day 4: Discovering AWS Athena's Capabilities

➠ Explored the versatility of SQL queries in AWS Athena
  - Investigated the range of SQL queries possible in AWS Athena, understanding how it interacts with data stored in S3 and the types of analysis that can be performed.
    
➠ Examined data partitioning strategies*:
  - Studied various data partitioning strategies and their impact on query performance in Athena, gaining insights into how partitioning contributes to cost savings.
    
➠ Learned about AWS Glue Data Catalog integration
  - Explored how AWS Glue Data Catalog serves as a central metadata repository and how it integrates with Athena to make S3 data easily searchable and queryable.

### Day 5: Exploring Data Integration and Orchestration

➠ Investigated AWS Glue's ETL capabilities
  - Researched AWS Glue's ETL features, understanding how it automates the extraction, transformation, and loading of data for analytics.
    
➠ Familiarized with AWS Step Functions' orchestration
  - Learned about AWS Step Functions and its ability to coordinate multiple AWS services into serverless workflows, grasping the basics of service orchestration.
    
➠ Reviewed error handling in Step Functions workflows*:
  - Reviewed best practices for implementing error handling in Step Functions workflows, appreciating the importance of resilience in service orchestration.

## 3️⃣ week 3

### 12th June 2024
- Online Session: Introduction to AWS DynamoDB, API Gateway, and Lambda Functions
- This week focused on building a serverless backend using AWS services like DynamoDB, API Gateway, and Lambda Functions. We worked on a project to create CRUD APIs for managing items in a DynamoDB table.

  <img src="https://media.licdn.com/dms/image/D5612AQFMBfd4HnZ0Iw/article-cover_image-shrink_720_1280/0/1699630089018?e=1724284800&v=beta&t=eG1tqVAl1EvKAu9J4LmAqAmFE5uxPQReQJEz88P8xiA" width="550" height="300"/>


### Here is the Outline of Week-3:
1. Create a table in DynamoDB
2. Write a Lambda Function as a Backend
3. Configure API Endpoints on API Gateway
4. Get /items
5. Put /items
6. Get /items/{id}
7. Delete /items/{id}
8. Configure API Endpoints with Lambda Code
9. Test Out APIs through Curl and Browser

## 📝 Day-by-Day Progress

### Day 1: Creating a Table in DynamoDB

➠ Create a table in DynamoDB
- Created a new table in Amazon DynamoDB. DynamoDB is a fast and flexible NoSQL database service for all applications that need consistent, single-digit millisecond latency at any scale. I configured the table with a primary key and other necessary attributes to store item data efficiently.

  ### Day 2: Writing Lambda Functions
  
➠ Write a Lambda Function as a Backend
- Developed a Lambda function to serve as the backend logic for our CRUD operations. AWS Lambda allows you to run code without provisioning or managing servers. The function was written in Python and included logic to interact with DynamoDB for various operations like retrieving, inserting, updating, and deleting items.

### Day 3: Configuring API Endpoints

➠ Configure API Endpoints on API Gateway
- Set up API Gateway to expose our Lambda functions as RESTful API endpoints. Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. Configured the endpoints for the various CRUD operations.

### Day 4: Implementing CRUD Operations

➠ *Get /items
- Configured the GET /items endpoint to retrieve all items from the DynamoDB table. This endpoint interacts with the Lambda function to fetch and return the list of items.

➠ Put /items
- Set up the PUT /items endpoint to add new items to the DynamoDB table. The Lambda function processes the incoming request and inserts the new item into the table.

➠ Get /items/{id}
- Implemented the GET /items/{id} endpoint to retrieve a specific item by its ID. The Lambda function uses the ID parameter to query DynamoDB and return the requested item.

➠ Delete /items/{id}
- Configured the DELETE /items/{id} endpoint to remove an item from the DynamoDB table based on its ID. The Lambda function handles the deletion process and ensures the item is removed.

➠ Configure API Endpoints with Lambda Code
- Linked the API Gateway endpoints with the corresponding Lambda functions. This integration allows API Gateway to invoke the correct Lambda function for each API request, ensuring the backend logic is executed properly.

➠ Test Out APIs through Curl and Browser
- Tested the configured APIs using curl commands and a web browser to ensure they work as expected. Verified that the CRUD operations (Create, Read, Update, Delete) perform correctly and that the APIs return the appropriate responses for different scenarios.


## 4️⃣ week 4

### *21st June 2024*
- *Online Session*: Introduction to AWS Bedrock, S3, and Knowledge Base Integration
- This week focused on building a knowledge base using AWS Bedrock, creating a vector store for efficient data retrieval, and interacting with the knowledge base using an agent.

  <img src="https://community.aws/_next/image?url=https%3A%2F%2Fassets.community.aws%2Fa%2F2Z6yg51zfyrwr7WzyFJ4zNsUukb.png%3FimgSize%3D2772x1102&w=3840&q=75" width="550" height="300"/>

### *Here is the Outline of Week-4:*
1. Create a Bucket
2. Upload my Resume
3. Create Knowledge Base in BedRock
4. Link S3 Bucket Object (Resume) with this Knowledge Base
5. Create Vector Store using Embeddings and Data Source
6. Test Knowledge Base using Generate Responses
7. Test Knowledge Base without using Generate Responses
8. Create an Agent
9. Connect it with Knowledge Base
10. Interact with your Resume

## 📝 Day-by-Day Progress

### Day 1: Setting Up the S3 Bucket and Uploading Resume

➠ Create a Bucket
- Created a new S3 bucket for storing objects. Amazon S3 is a scalable object storage service that allows for the storage and retrieval of any amount of data at any time.

➠ Upload my Resume
- Uploaded my resume to the S3 bucket. This step is crucial for linking the resume to the knowledge base in Bedrock.

### Day 2: Creating and Linking Knowledge Base in Bedrock

➠ Create Knowledge Base in BedRock
- Created a knowledge base in AWS Bedrock. Bedrock is used for building intelligent applications with comprehensive knowledge management and natural language understanding capabilities.

➠ Link S3 Bucket Object (Resume) with this Knowledge Base
- Linked the uploaded resume from the S3 bucket to the knowledge base. This allows Bedrock to use the resume as a data source for generating responses.

### Day 3: Building and Testing the Vector Store

➠ Create Vector Store using Embeddings and Data Source
- Created a vector store using embeddings to enable efficient data retrieval. This involved transforming the resume data into vector embeddings that Bedrock can use for quick search and retrieval.

➠est Knowledge Base using Generate Responses
- Tested the knowledge base by generating responses from the linked resume data. This helped verify that the knowledge base correctly understands and retrieves information from the resume.

➠ Test Knowledge Base without using Generate Responses
- Conducted tests on the knowledge base without using the generate response feature to ensure it can handle direct queries and return accurate information.

### Day 4: Creating and Connecting an Agent

➠Create an Agent
- Created an agent in AWS Bedrock. Agents in Bedrock are responsible for interacting with users and providing responses based on the knowledge base.

➠Connect it with Knowledge Base
- Linked the created agent with the knowledge base to enable it to access and retrieve information from the resume stored in S3.

### Day 5: Interacting with the Resume

➠Interact with your Resume
- Interacted with the resume through the agent. This involved querying the agent to retrieve specific information from the resume, ensuring the setup was functional and effective.

## Problems faced after few Days of competion of Internship

- After completion of Internship on 30 June I came across the mails that my billing charges are getting than we are expecting.
- Then I contact Amit Aurora sir and he helped me and we come to know that my bedrock,KMS,Agent Services are still on.
- then we conatact to AWS support and wrote them that we are student and we were exploring the servies and went dee,it was not intentionally
- then we go reply for few days and i reply them back everyday like they were mailing me to xyz servies are still on and terminate them
- iused to terminate them accordingly and sending them attachment for proof and on 15 july the billing things was sorted out
- all thnaks to AWS and Amit sir for Guiding me


## 🤝 Connect with Me

- LinkedIn: [[https://www.linkedin.com](https://www.linkedin.com/in/viken-hadavani-27b6412b3?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bc%2BtFz8i0SqaVmf395szcFw%3D%3D)]

- Email: [vikenhadavani@gmail.com]


Thank you for visiting my project! Feel free to reach out if you have any questions or feedback. ✨
