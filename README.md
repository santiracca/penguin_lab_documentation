# Penguin Lab
This document is meant to serve as a guide to learn how to work in the Penguin Lab. It outlines the various different processes that different roles must follow in order to fullfil their requirements

The lab works by creating an interface between clients and developers that simplies the project management for both parts. The interface is presented currently as a web application where a user can either create a client and/or developer account. The main features are

- Manage communication between client and developers
- Offer clients a simple way to create, develop and manage software projects.

## Overview of Main Process
The client creates a request in the lab. A request can be any type of development needed for their project such as new features, new designs, bug fixes,etc. A request has one of four possible status 
- 1 For Estimation
- 2 Estimated
- 3 For Development
- 4 Completed

In order to complete a request, a developer must first provide an estimation of how many credit hours it would take to implement the request and subsequently implement the feature. 

## Process Details
### Step 1: FOR ESTIMATION -> ESTIMATED
When a request get created the status is set to For Estimation. A developer must estimate how many credit hours it would take to implement the specific request and communicate this to the client by updating the request status to Estimated. 

The estimation process consists of breaking the client request (usually very abstract) into smaller actionable sub-tasks that we call issues. The issues are concrete solutions of implementation and provide a clear description of what to do in order to implement the request. The time it takes to create all the necessary issues for solving the request are the ***Credit Hours used for estimation***. For every issue you create you provide an estimation of how many credit hours it would take to implement, and the sum of this accros all the issues of a request provides the total ***Estimated Credit Hours for Implementation***.

Currently the issues are created in a seperate project management tool such as Jira in order for the client to always have visibility on the progress of the project. The lab is currently being developed to automate this process. 

Since various different developers could potentially be working in a project and the technology used for a request can be different. The Lab usually provides a project manager role that acts as an intermediary between the client and the developers in order to centralize and facilitate communication.

The project manager receives the client request and assigns developers to create the issues. The developers then follow the estimation process to provide the project manager the issues needed to fulfill their particular scope of the request. The project manager then compiles the issues from all developers and communicates them to the client in the project management tool of use. 

The status of the request then changes to ESTIMATED.

#### Important Points When Estimating
- The estimation should not be rushed as we expect well-researched and confident solutions for every issue. This effectively means to not worry about long estimation hours if this is NEEDED to create all the necessary issues.
- When estimating the credits for implementation, please remember to include credit hours for code reviews, testing and fixes. You dont have to create an issue for this, but it is very common to see new developers UNDERESTIMATING the implementation time because they don't consider the time to review the code, test it out and provide fixes before completing the request.

### Step 2: ESTIMATED -> FOR DEVELOPMENT
The CLIENT must then choose whether or not to set the status to FOR DEVELOPMENT, and update the the request in the lab. If this happens we move to step 3

### Step 3: FOR DEVELOPMENT -> COMPLETED
When the status is set to for development, the developer can start working on implementing the specific issues that were created.

`//TO DO: INSERT CODE QUALITY OUTLINE HERE`


After completing the issues a developer submits a pull request that gets reviewed and feedback is provided. If the pull request gets approved and the implementation passes testing then status of the request is set to completed and the request is finished.

`//TO DO: OUTLINE TESTING TYPES AND PROCEDURES`








