# Automated Github Organization (and Team) Invites
[![Code Climate](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites/badges/gpa.svg)](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites) [![Issue Count](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites/badges/issue_count.svg)](https://codeclimate.com/github/thundergolfer/automated-github-organization-invites)

> Quickly host a webpage to allow people to click and receive an invite to your Github Organization and an (optional) default team.

<p align="center">
  <img src="auto-invites-example-ui.png"/>
</p>

### Features

* Validates submitted Github usernames
* Links in your Github Organization's avatar/image
* Lightweight
* Optionally auto-invite to a team inside the organization

### Get It Right Now

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

All you have to do is

1. Click **Deploy to Heroku**
2. Fill in the **Environment Variables** when prompted. These will be a *[Github Access Token](https://github.com/blog/1509-personal-api-tokens)*, which should have Organization privileges enabled, and a *GitHub Organization name*, and a *background color*. The choices are `{blue,green,grey,pink,red,white}`. If you don't enter one of those strings it defaults to 'white'. Lastly an optional *GitHub Organization team* can also be specified if you want your users to auto-join a default team.

#### All Done! Just share the Heroku App's URL to people and they'll be able to get themselves an invite to your organisation.


### Credit 

Thanks to *[Code, Applied To Life](https://medium.com/code-applied-to-life/automated-github-organization-invites-3e940aa27040#.sikfvzyaj)* for their efforts which were used as a base for this.

## BYU-I Notes

We can run one free app on Heroku (https://signup.heroku.com/). The course lead will create a new app for each semester to automate the process of students joining the group and the respective semester team. We will just keep the link active for the final project of CSE-250.  All other members can be manually added throught Github.

1. _App name:_ whatever you want
2. _BACKGROUND_COLOR:_ blue
3. _GITHUB_TOKEN:_ https://github.com/settings/tokens and make sure you have admin access to the group.
4. _ORGANIZATION_NAME:_ byuids-resumes
5. _TEAM_NAME:_ Under [CSE-250](https://github.com/orgs/byuids-resumes/teams/cse-250) create a new team for the current semester with year (e.g fall_2020)
6. Deploy app and use link _App name_.herokuapp.com
7. delete app at the end of the semester under app settings https://dashboard.heroku.com/apps/_App name_/settings
