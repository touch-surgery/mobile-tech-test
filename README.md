Hi

We would like you to spend a few hours on the following technical task:

Create an app with two screens:

# Procedure Page:
This should be the home page of the app. It should have a list of procedures cards/cells, each with a thumbnail image and a name. This information can be acquired from the procedures endpoint (/procedures). Clicking on one of the procedure cards/cells should take the user to the next page.

# Procedure Details Page:
This page should present the details of the procedure selected. There should be a card image at the top of the page, the title of the procedure and then the list of phases for the procedure. Each phase should contain a thumbnail image and a name. This information can be acquired from the procedure details endpoint (procedures/$PROCEDURE_ID) with the procedure id as a parameter, e.g procedure/procedure-ETH_WedgeRes

# General Instructions:
- Do not fork the project. Do not create pull requests to this project. Clone it on your local machine.
- Upon completion, send us a zip containing your project.

## Android Instructions:
- Do not include build folders or IDE specific files.

## iOS Instructions:
- *DO* include the Podfile or Cartfile.
- *Do NOT* include build folders or dependency folders.

# Endpoints
- The procedures list will be available at `https://staging.touchsurgery.com/tech-test/procedures` 
- Procedure details are available at `https://staging.touchsurgery.com/tech-test/procedures/$PROCEDURE_ID`

For example `https://staging.touchsurgery.com/tech-test/procedures/procedure-TSC_CemCup`

# Technologies to use:
It is entirely up to you what libraries you use, just use the ones which you feel represent your skills the best. We are interested in how you architect mobile applications so pay attention to which design pattern to use and be prepared to answer questions about why you chose the pattern you did.
A good architecture would be highly appreciated

# Unit tests:
TDD is a big part of how we work here are Touch Surgery. Please make sure that you write your code in a testable way and that you include some unit tests.

# Bonus Points:
For additional points, please write a few paragraphs on how you would handle data persistence / caching for use when offline. There are many ways to address this problem, we would be interested in hearing about your prefered approach. Examples of how you have solved this issue in the past would be helpful.
