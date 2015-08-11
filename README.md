### FishBrain Catches Master/Detail

The goal of this project is to assess iOS development skills. It is designed to be challenging, and evaluate all aspects of development.

- Project Name: Fishbrain Catches Master/Detail View
- Project Goal: Creating a simplified version of the current app master/details view with limited functionality
- Technology: Objective-C or Swift 
- Deliverables: The solution should be sent using the greenhouse.io link that will be provided during the interview process.

**Mockups:** https://s3-eu-west-1.amazonaws.com/fishbrain/misc/Mobile+task.jpg

**Description:** Rebuild the catches view from the current Fishbrain app with filters in a master/details fashion. When opening the catch you should display some basic data and the full picture. Please skip the date/weight/length filters.

**API to consume:** http://rutilus.fishbrain.com is our production RESTful JSON API, and since some endpoints are publicly available we can use them for this assignment.

The API has the concept of verbosity. When requesting a specific resource we can specify the amount of details we want to receive. It is easiest to play around with multiple levels of verbosity and see the output.

**Example querying of the API:**

- Get paged catches - https://rutilus.fishbrain.com/catches?page=3
- Get specific catch - https://rutilus.fishbrain.com/catches/81?verbosity=3

- Filtering by specific parameter - https://rutilus.fishbrain.com/catches/81?verbosity=3&q[species_id_eq]=258

- supported filters: species_id_eq, weight_lt, weight_gt, owner_id_eq, description_cont and more. 

**Guidelines**

The solution needs to contain tests and the design/organization of the application code should be production ready. 

The application has to be runnable and working without major issues.

Ask any questions related to the implementation, but stackoverflow and google are your first stop for any obvious questions.

**What is this?**

This repo contains the job assignment for potential IOS developers at Fishbrain, you can apply for a job at: jobs@fishbrain.com

