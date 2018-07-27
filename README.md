# Griffin Group Global Test Automation Challenge

Hi! Thank you for your interest in [Griffin Group Global][g3website]. Our evaluation process begins with an open-ended challenge that we will discuss during your interview. There is not one correct way to approach this challenge. Rather, we would like to see your approach and your creativity in solving the problem.

We appreciate that any challenge represents an investment of your time. We hope you see the value in having a code sample that is relatable to both of us for the interview. Should you be unsuccessful, you should feel free to use the code you developed for this challenge in any way that you would like.

If you are successful, then we will set up an in-person interview and use this code as the starting point in our conversation.

# The Challenge
Griffin Group Global creates REST-based microservices that are presented in a variety of ways. We use iOS native Swift, Android-based Java and JavaScript-based frameworks such as React for creating responsive web-based presentations.

The challenge is to create an automated test for the [Star Wars API][swapi] website. The idea is for you to have fun and be creative with your tests.

## Minimum Challenge Requirements
We would like your submission to offer a minimum capability. The criteria are:
- Provide a test automation suite that verifies the [Star Wars API][swapi] for at least one of the following browsers:
  - chrome
  - firefox
  - headless/phantomjs
- Verify the existence of the [home page][swapi]
  - Verify through a request that the home page will show the Millennium Falcon's information by submitting a request using starships/10.

## Where to concentrate your effort
In automated testing, there are many areas that could be addressed. While implementing the minimum requirements, please feel to implement one or more items in these areas. Please do not feel limited to these areas if you would like to add your take on automated testing.

- validation of JSON format data
- Running the test suite from [docker containers](https://hub.docker.com/u/selenium/)
- printing out detailed reports
- http header based validation
- secure TLS based testing

# Prerequisites
- A basic understanding of source code control, [git][git-scm] is required.
- You must make your code available via a [GitHub][github] account.

# Getting Started
1. Fork this [repository][repository].
1. Clone the fork to your personal machine.
1. Start coding.
1. Commit changes to your fork as you see fit.

# Submission

When you are comfortable with your results, please email your fork to
[g3-dev@griffingroupglobal.com](mailto:g3-dev@griffingroupglobal.com). Please keep your emails short and to the point.

Any specific notes or further information you would like to add about your submittal, should be included in the GitHub project, as additional [Common Mark][commonmark] notes.

Do not feel as though you must create a public fork of this repository. You are free to create a throwaway GitHub account or private fork. In those cases, please let us know so that we may send you the GitHub IDs to add to the repository.

# Evaluations

We realize there are many items to look at when creating an automated test suite. Please do not feel like like you have to do everything. Please feel free to use any technology you wish. Use your strengths to your advantage. Give us a heads up by documenting your code to let us know where and why you concentrated on certain items.

As you develop your solution, you may have ideas on other avenues to pursue. Please feel free to include them inline as documented source or as additional [Common Mark][commonmark] compliant notes in your fork.

We look for creativity, originality, comprehensive testing and a good user experience in your test suite.

We look for readability, good architectural decisions, modularity, and a solid approach to testing.

# License
This project is [MIT licensed][mitlicense].

[g3website]:https://www.griffingroupglobal.com
[git-scm]:https://git-scm.com/
[github]:https://github.com/
[nodejs]:https://nodejs.org/en/
[TDD]:https://en.wikipedia.org/wiki/Test-driven_development
[ES6]:http://www.ecma-international.org/ecma-262/6.0/
[eslint]:https://eslint.org/
[airbnb-eslint]:https://www.npmjs.com/package/eslint-config-airbnb
[mocha]:https://mochajs.org/
[repository]:https://github.com/GriffinGroupGlobal/frontend-challenge
[mitlicense]:https://en.wikipedia.org/wiki/MIT_License
[commonmark]:https://spec.commonmark.org/
[swapi]:https://swapi.co/