# Github Airtable - Issues
> `Airtable` integration with `GitHub` `Issues` for bug and feature request tracking

- When a `GitHub` `Issue` is created it will appear in `Airtable` as a searchable and filterable list

## Prerequisites
- [Airtable](https://airtable.com/)
	- New or existing account

- [Node](https://nodejs.org)

- [Docker](https://docker.com) & [Docker Compose](https://docs.docker.com/compose/)
	- [MacOS](https://docs.docker.com/docker-for-mac/install/)
	- [Linux](https://docs.docker.com/v17.12/install/linux/docker-ee/ubuntu/)

## Docs & Guides
- ##### Airtable
	- [Airtable Guide](https://guide.airtable.com/)

- ##### Issues
	- [Mastering Issues](https://guides.github.com/features/issues/)


## Methods
- ##### Logger
	This function chains series of other function together using a lightweight
	wrapper around the request-promise library, FaaS-Chain.

- ##### Submit To Airtable
	Takes the request information from the github webhook and adds the item to the
	Airtable sheet.

- ##### Lowest Issue Count
	Grabs the team member with the lowest issue count

- ##### Assign Record To
	Assigns the issue to a team member. In this instance, the team member with
	the lowest issue count

- ##### Update Github Issue
	Adds an assignee to the issue in GitHub

- ##### Demo
	[Quick video demo on YouTube](https://www.youtube.com/watch?v=6dORD3_E5aU&t=1s)

	![alt text](https://s3.amazonaws.com/aafrey-random/github-to-airtable.gif)


## Github Repo
```bash
echo "# airtable-github-issues" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/flavioespinoza/airtable-github-issues.git
git push -u origin master
```
# airtable-github-issues
