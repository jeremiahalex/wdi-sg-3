
# WDI SG 3
This is the main workspace for WDI SG 3. Here you will find all the course materials: assignments, starter-code etc.   
Lesson notes will be kept in the [wiki](https://github.com/jeremiahalex/wdi-sg-3/wiki).   
Our lesson schedule is updated weekly in our [google calendar] (https://calendar.google.com/calendar/embed?src=generalassemb.ly_hur7v9j9m8e2a463ls76b5ipfs%40group.calendar.google.com&ctz=Asia/Singapore).

If you have issues you can [raise them as issues](https://github.com/jeremiahalex/wdi-sg-3/issues).

__You must also use this repo to notify of your completed homework. Follow the Contribution Instructions below.__

## Read Only Instructions
- The quickest way to get a copy of the files on your system, is to just clone this repository to your local machine. 
    + `git clone https://github.com/jeremiahalex/wdi-sg-3`
    
## Contribution Instructions

- So you can notify about project completion you should fork this repository
    + Hit the fork button on the top right (this stores a copy of it on your own github)
- Clone your forked repository on your local computer
    + `git clone http://url_of_your_fork_on_github.git`
- Add an upstream, so that your local copy's remote is pointing to my repository on Github (this repository)
    + Move into the the repository `cd sg-wdi-3`
    + `git remote add upstream https://github.com/jeremiahalex/wdi-sg-3`
    + `git pull upstream master`
- Create your own directory in the `students/` directory
    - `cd students` to move into the students directory
    - `mkdir givenname-familyname` to create your own directory
    - cd `givenname-familyname` into your own directory
    - `touch README.md` to create a new README.md file
    - Update the README file to include your name, and links to your online homework and assignments

### Update your Assignments README.md

- Update your README.md file to include a link to your latest homework/project repo
- Push to your local version (the one that you forked)
    + `git add --all`
    + `git commit -m "Your commit message"`
    + `git pull upstream master` to check you have the latest version before making any changes
    + `git push origin master`

## Create a Pull Request on GitHub

- Go to your repo on the GitHub website
- Click on the Pull Request tab
- Click on the `New Pull Request` to create a new Pull Request
- Make sure the destination for the pull request is set to my repository
- Add the following in your comments:
    + How difficult did you find this (out of 10)? 0 being no problems at all, 10 being impossible
    + Was there anything that you struggled with?
    + Is there anything that you'd like some further information on?
    + Roughly, how long did it take?

Note: If you don't mention anything in the comments, I'll assume you had no problems at all with it!
