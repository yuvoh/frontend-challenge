# Yuvoh Frontend Challenge
## GitHub Repository App

Thank you for taking the time to do our technical test, we know they take a while to complete, but they provide us invaluable information to ensure we hire the best people!

You will be building a small web app that integrates with the GitHub API. You'll find below the product and technical specifications your app should meet. The task is open-ended, so build the app as you see fit, and feel free to extend the functionality with some idea of your own if you wish.

## Specifications

#### Features
The app should:
* Have a single view showing a list of repositories pulled from the GitHub API
* Handle pagination appropriately (buttons, or an infite-scrolling list, or something else entirely)
* Have a search box allowing the user to filter repositories by a query string
* Show the following data for each repository:
  * Title (which links to the repository page on GitHub)
  * Description
  * Star count
  * Programming language
  * Repository owner name and Gravatar (which links to their profile on GitHub)

#### Design
You should design the app to fit in with GitHubs existing colour scheme and modern flat style. It does not need to look like the existing product, just feel like it may have been produced by the GitHub team.

The app should be responsive so that it can be viewed on desktop and mobile nicely. 


#### API
The [GitHub API](https://developer.github.com/v3/search/#search-repositories) looks as follows:
https://api.github.com/search/repositories?q={query}&page={page_number}&per_page={results_per_page}

Substituting `query`, `page_number` and `results_per_page` with appropriate values.

The fields in the JSON response you will need to use are: 
`name`, `url`, `description`, `language`, `stargazers_count`, `owner.avatar_url`, `owner.login`, `owner.url`

## Guidelines
* You may use any libraries, frameworks or preprocessors that you wish
* Spend as much or as little time as you wish, but try to complete the core functionality if possible
* Focus on good development practices rather than flashy features


## Submission
Your project should contain everything needed to run your app, *excluding* your ```node_modules``` folder.

Please include a README file explaining the step(s) needed to run your app along with the answers to the following questions:

1. How long did you spend on the challenge?
2. What would you add to your solution if you had more time?
3. Which part of your solution are you most happy with?
4. Is there anything about the challenge you did not like?
5. Any other comments!

You can either place your project in a ZIP file and email it to us **OR** upload it to a GIT repository and send us a link.

Thanks for your time, and happy coding!
