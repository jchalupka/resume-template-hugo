---
title: "Content"
date: 2018-08-12T14:37:23-04:00
draft: false

first_name: Jordan
last_name: Chalupka
email: jchalupk@uoguelph.ca
website: chalupka.me
phone: 226-932-9223

skills:
  header_name: Skills
  list:
    - title: Programming Languages and Frameworks
      text: Nodejs, Javascript, Go, Python, Express, Django, C.
    - title: Amazon Web Services
      text: Lambda, API Gateway, Cloudwatch, S3, CloudFront, EC2, IAM, Terraform.
    # - title: Te Python, AWS, Terraform.

    - title: Design & Methodologies
      text: Zen of Python, the Twelve-Factor Application, Microservice Architecture.
    # - title: Web & Design
    #   text: HTML5, CSS3, Javascript (ECMAScript 6), Webpack, Babel, Bootstrap.

    # - title: Interests
    #   text: Digital Art, Travel, Design, Technology, Photography, Skiing.

work_experience:
  header_name: Work Experience
  list:
    - company_name: Kira Talent
      start_date: May 2018
      end_date: September 2018
      job_title: Software Developer Intern
      bullets:
        - Demonstrated initiative by proposing and developing a highly cost-effective spelling and grammar checker microservice using the open source project "LanguageTool" as well as AWS Lambda and API Gateway.
        - Designed and developed a scalable and low-cost video conversion microservice using AWS Lambda, API Gateway, Elastic Transcoder, S3, CloudFront and the Twelve-Factor App methodology.
        - Developed across the stack to add tests, as well as new features to a large Django project.
    - company_name: Adknown Inc.
      start_date: May 2017
      end_date: January 2018
      job_title: Software Engineer Intern
      bullets:
        # - Created several user interfaces using web development skills to interact with back-end services.
        - Developed an automated domain registration system using Nodejs, Lambda and Step Functions.
        - Created a Jira Plugin to add custom time management functionality to Jira using Nodejs and Express.
        - Helped several coworkers learn Nodejs and gave a presentation to introduce the development team to AWS Lambda and Step Functions.
        # - Improved development skills by working on a large code base,  fixing bugs, and adding many new features.

    # - company_name: Google Analytics Setup and Support
    #   start_date: January 2017
    #   end_date: October 2017
    #   job_title: Freelance
    #   bullets:
    #     - Set up Google Analytics for car dealerships in Florida through UpWork.
    #     - Created a tracking tool for dealerships to mothor the site's usage.

personal_projects:
  header_name: Personal Projects
  list:
    - project_title: Knock Knock Joke Twitter Bot
      start_date: July 2018
      end_date: August 2018
      bullets:
        - Uses webhooks to trigger an AWS Lambda function behind API Gateway which answers to knock-knock jokes and joke requests.
        - Lambda function is written in Golang and utilizes the Twitter API.
        - AWS services managed using Terraform.
  
    - project_title: Library Renewal Automator
      start_date: May 2018
      end_date: June 2018
      bullets:
        - Automates the renewal of library books using the Chromeless library.
        - Runs a headless version of the Chrome browser on AWS Lambda to allow user actions to be simulated using javascript.
        - AWS CloudWatch is used to schedule the Lambda to run whenever books need to be renewed.

    - project_title: Opposite Day
      start_date: March 2018
      end_date: April 2018
      bullets:
        - A npm module which takes an article and replaces all of the words with their opposite word in order to create an entertaining opposite version.
        - Demonstrates usage of the Datamuse API, as well as modern functional javascript.

    # - project_title: University of Guelph Course Map
    #   start_date: June 2017
    #   end_date: October 2017
    #   bullets:
    #     - Creates an easy way for students to see a tree of prerequisite courses.
    #     - Used Casper.js to scrape course information from the University of Gueloh course selection website.
    #     - Stored course information in JSON using Dynamodb.
    #     - Created a Graphql API to efficiently query specific course data.
      
    
    # - project_title: YouTube Chrome Extension
    #   start_date: July 2016
    #   end_date: August 2016
    #   bullets:
    #     - Written with Javascript and JQuery.
    #     - Created a QR code of the link to the video being viewed at the exact time in the video.
    #     - Make use of the Chrome API and QR code generator web API (qrserver.com).

    # - project_title: CDC Data Analysic
    #   start_date: January 2016
    #   end_date: May 2016
    #   bullets:
    #     - Manipulated large amounts of data from Center of Disease Control records ranging in years from 1979 - 2014.
    #     - Created a system to analyze birth and mortality data from the CDC.
    #     - Created visual representations using statistical knowledge to easily see relations in the data.

education:
  header_name: Education
  list:
    - major: Software Engineering
      minor: Statistics
      other:
        - Co-op
      school: University of Guelph
      start_date: September 2015
      end_date: Present
---
