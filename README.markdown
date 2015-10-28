# Moviefone Info and Best Practices
This document is intented to provide some information in regards to developers and overall developing guidelines. 

These guidelines should be followed at all times. If you feel that this need to be updated, please submit your request [here](https://github.com/gmorales-phunware/PW-Objective-C-Style-Guide/issues/new).

## Best Practices
Starting 1.5, this project will follow [Git Flow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow). 

We will begin by creating a 1.5 branch. 
We will consequently create a development branch. 
For every feature/ticket created, each developer will branch out from the development branch and work on the feature/ticket. 
Once the work is completed the developer will then make a pull request for the lead developer to merge into the development branch. 

The lead developer will be responsible for checking the quality of the code and ensure it meets the project best practices and code style. If this does not meet the requirements, the pull request will be rejected. 

Merging into master should only be expected to happen at the time of release candidate. Any prior releases can be greated from the development branch. 

Only the lead developer will be responsible for merging into master. This should only happen after QA has given the green light. It should also be noted that the Dev manager can perform code reviews during any point of the development process. 

Please take a moment and read the [Pull request](https://github.com/gmorales-phunware/contributing-guidelines/blob/master/CONTRIBUTING.md#pull-requests) guidelines. 

### iOS
We currently have no code style best practices. I would like to propose this one: 

[PW Code Style](https://github.com/gmorales-phunware/PW-Objective-C-Style-Guide)

### Android
[Android Code Style](https://google.github.io/styleguide/javaguide.html)

[Android Code Conventions](http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html)

### Both Platforms
I currently see that both projects are lacking documentation in the code base. Let's make it an effort to document as thoroughly as possible. 

I would also like to come into a habit of having the following:
 
* Weekly code reviews
* Implementing unit testing


## Jira
As we all know, we use JIRA for our tickets. This however can become increasingly disordered. I need your help with this and would like to recommend the following: 

* Tickets that require Trista's attention but are not related to the apps, please post the request on Basecamp instead of JIRA. You can feel free to create new issues here: [iOS](https://github.com/phunware/brandme-app-moviefone-ios/issues/new) or [Android](https://github.com/phunware/brandme-app-moviefone-android/issues/new).
* All tickets created need to include: 
	* Epic
	* Label
	* Detailed description
	* Steps to reproduce (If applicable)

Please note that any tickets without detailed description, will be reassigned to whoever created them. 

## Lead Developers
I would like for you to have added responsibilities that can be worked on when time allows. 

* Generate a detailed README for github. 
* Review our current best practices and see if we can improve. 
* Document and ensure code base is documented. 
* Cross train each other and any developer that may come to the team. 
* Help with the sanity of the tickets in JIRA. 
* Tell me if i'm being a little over the top. =)


I don't know about you but as a developer, I want to keep learning and making sure that I'm doing things properly can not only guarantee that I will improve but sometimes my way of thinking may not be the best. (tired, frurstrated, bored, etc). 

I know these changes may not change the company as a whole but at least we can help each other and we can set the standard for other projects. 

## Contributing to this project
If you have change or update request, feel free to help out by sending pull requests or by [creating new issues](https://github.com/gmorales-phunware/MoviefoneInfo/issues/new). 

Please take a moment to review the guidelines:
* [Bug reports](https://github.com/gmorales-phunware/contributing-guidelines/blob/master/CONTRIBUTING.md#bugs)
* [Feature requests](https://github.com/gmorales-phunware/contributing-guidelines/blob/master/CONTRIBUTING.md#features)
* [Pull requests](https://github.com/gmorales-phunware/contributing-guidelines/blob/master/CONTRIBUTING.md#pull-requests)	