# BackEnd Challenge 003

For us, it's not all about an outstanding CV or a long list of qualifications. We are far more interested in your approach when faced with a concrete challenge. What is your way of thinking? How do you tackle the problem? Which tools do you choose?

In order to gauge these qualities, we have created a challenge for you to complete. This is a simplified case which illustrates the kinds of situations we have to deal with on a daily basis.
This challenge is an opportunity to demonstrate your capabilities and to show us your coding craftsmanship.

There are no time limitations, but our suggestion is that you spend no more than a few hours completing the challenge.
We are not after a bullet-proof solution. What is important is a clean, maintainable and intuitive result.

Create it in your own way and use the tools you are most comfortable with. Show us your skills!

## Challenge Description

(Versioned from here: https://gist.github.com/tadast/5642683)

### The Experts friendships

We want to create a SocialNetwork website based on the terms of interests and friendships connections between our contacts.

### Create a Member

* We enter a **name** and a **personal website address** and a member is created.
* When a member is created, all the heading (h1-h3) values are pulled in from the website to that members profile.
* The website url is shortened (e.g. using http://goo.gl)

### Define friendships

* After the member has been added, I can define their friendships with other existing members. Friendships are bi-directional i.e. If David is a friend of Oliver, Oliver is always a friend of David as well.

### List all Members

* The interface should list all members with their name, short url and the number of friends.

### Info of a Member

* Viewing an actual member should display the name, website URL, shortening, website headings, and links to their friends' pages.

### Making introductions

* Now, looking at Alan's profile, I want to find experts in the application who write about a certain topic and are not already friends of Alan.

* Results should show the path of introduction from Alan to the expert e.g. Alan wants to get introduced to someone who writes about 'Dog breeding'. Claudia's website has a heading tag "Dog breeding in Ukraine". Bart knows Alan and Claudia. An example search result would be Alan -> Bart -> Claudia ("Dog breeding in Ukraine")

* Optional: prefering h1 over h2 and shorter introduction paths when ordering results.

### Implementation Notes

Please don't get caught up trying to implement the perfect solution, we are interested in the most simple and functional solution. We expect the final delivery to be stable, so focus on simplifying the functionalities to allow a working solution to be developed in a few hours.

### Programming Requirements

The backend must be Ruby. The frameworks, gems, and databases are all up to you.

For the frontend, we appreciate if it looks human friendly, but it is not necessary to be fancy. (There are a lot of OpenSource/Free templates and HTML/CSS frameworks that do a good job.)

### What We Assess

- Legible, understandable, clean and maintainable code
- Wisely choosen tools, techniques and/or frameworks

## Submission Instructions

1. Fork this project
1. Complete the task and push on your own fork. (Nice, atomic and iterative commits are welcome)
1. Include instructions of how we can make it to work
1. Submit a pull request
1. Send an email to hr@daliaresearch.com to review your solution

And, of course, don't hesitate to **contact us with any questions** you have. Send all your technical queries to: [it@daliaresearch.com](mailto:it@daliaresearch.com)
