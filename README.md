# Learn API and Postman - Trello API

## Introduction and description:

Welcome to the repository dedicated to learning to write my first basic Postman requests and tests for the Trello API.

**The main tests are:**
- Check status code is 200;
- Check response time is less than 200ms;

**The things that I learned from it:**
- Create requests for methods POST, GET, PUT, DELETE;
- Variable management (global variables, environment variables, collection variables);
- Managing catalogs and a large number of requests;
- Generating random variables;
- Writing simple tests;
- Navigating on JSON and catching his values into variables;
- Writing pre-requests and after-request in code;
- Sending files;

### This repository contains the following files:
- Endpoints List (MS Excel and PDF) - Here is a list of endpoints for which I wrote tests;
- Trello API.postman_collection.json - Postman file with all requests that you can import to your Postman;
- organization_logo.png - Image needed for one request that is sent;
- Postman - tips & screens (MS Word and PDF) - Tips on what to do to make it work for you and screenshots of how it looks if you don't want to do it;

**If you don't want to download it, configure and set up accounts you can only view the screenshots from this PDF and see how all these requests work in the following video:**</br>
[YouTube -> Learn API and Postman for Trello API - Requests work](https://youtu.be/gywSosSil0E)

## Startup instruction and what you need to know:</br>
*The picture version is in file -> Postman - tips & screens*

**Before you send requests you need to get your own key and token for your Trello Account:**
1. Create account on Trello (www.trello.com).
2. Create account on Trello Developers (https://developer.atlassian.com/cloud/trello/).
3. Go to https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/ and read base informations.
4. Next go to https://trello.com/app-key and get your API key.
5. On that same site click „Token” word and go with their instructions to get your own token.

Now you can add your key and token into variables. Also you should create second normal Trello Account on your second e-mail and add this e-mail too.

In „Organizations tests” one request need upload a file as logo. This file is also in repository. To make sure it works for yours Postman you need to set in settings path or (even better) „Allow reading files outside working directory” on ON.

To run my requests on your Postman you should download repository and in Postman’s settings import this .json file.
