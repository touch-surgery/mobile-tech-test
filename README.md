Hi

We would like you to spend a few hours ( no more than 3 ) on the following technical task:

Create an app with two screens:

Procedure Page:
This should be the home page of the app. It should have a list of procedures cards/cells, each with a thumbnail image and a name. This information can be acquired from the /procedures endpoint. Clicking on one of the procedure cards/cells should take the user to the next page.

Procedure Details Page:
This page should present the extra details of the procedure. There should be a card image at the top of the page, the title of the procedure and then a list of each of that phases that are contained within a procedure. Each phase should contain a thumbnail image and a name. This information can be acquired from the /procedure_details endpoint with the procedure id as a parameter, e.g procedure_details/procedure-TSC_DPapproach

Setting up the local server:
 - fork this repository, and clone to your machine
 - cd into the root directory
 - on terminal run: ```json-server --watch db.json```
 - The apis will be available at http://localhost:3000/procedures and http://localhost:3000/procedure_details


Technologies to use:
It is entirely up to you what libraries you use, just use the ones which you feel represent your skills the best. We are interested in how you architect mobile applications so pay attention to which design pattern to use and be prepared to answer questions about why you chose the pattern you did.

Unit tests:
TDD is a big part of how we work here are Touch Surgery. Please make sure that you write your code in a testable way and that you include some unit tests. 

Bonus Points:
For additional points, please write a few paragraphs on how you would handle data persistance/caching for use when offline. There are many ways to address this problem, we would be interested in hearing about your prefered approach. Examples of how you have solved this issue in the past would be helpful.