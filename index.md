# Cats Project

### Preface:
We love pets @ Bento!  So we wanted to come up with a project that used "awww" like cat pics (we love dogs too!) and cat facts.  What we hope to get out of this project is a general sense of your approach to front-end development.  This README provides just about all the info needed to get started, but if you have any questions, feel free to reach out to your Bento contact for clarification.  Good luck and happy coding :).

### Description:
You will be building a Pinterest-like photo wall using cat photos and facts! (see simple example below)  The wall should be built using one of the frameworks outlined in the Specs section and data needed will be provided by two separate APIs.  There are a few features that we would like the img wall to have outlined in the Specs section but feel free to expand on those specs.
![](cats.gif)

### Getting Started:
We use a variation of the fork and pull workflow.  So to get started do the following:
- Fork this repo
- Clone forked repo
- Checkout new branch `feat.img-wall`

To submit your code do the following:
- Push `feat.img-wall` to forked repo
- Create PR from `yourForkedRepo:feat.img-wall` onto `bentosRepo:master`

### Specs:
Some of the following specs are more ambiguous in nature.  Feel free to interpret those specs in the way that you deem is best.
- Use one of the following frameworks to build the project: Angular (v1 `||` v2), React, or Vue
- Use cat images from http://thecatapi.com/api/images/get?format=xml&results_per_page=25
- Use cat facts from http://cors-proxy.htmldriven.com/?url=https://catfact.ninja/facts?limit=25
- Allow users to sort photos alphabetically by the last word in the cat fact
- Allow users to "favorite" an image (with attached fact) and allow users to view only favorited images
- Allow users to view one photo and fact at a time

### What we're looking for
- Quick Setup: running `npm install` `npm start` should let us see cats after merging your PR and pulling down `master`
- Code Readability: we'll be reviewing your code
- Project Extensibility: we may ask you to add various features during the onsite
