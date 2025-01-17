---
title: React Demo Client
reviewers: Dr Marcus Baw
---

# React Demo Client

{% set repository_name="rcpch/digital-growth-charts-react-client" -%}

[![Github Issues](https://img.shields.io/github/issues/{{ repository_name }})](https://github.com/{{ repository_name }}/issues)
[![Github Stars](https://img.shields.io/github/stars/{{ repository_name }})](https://github.com/{{ repository_name }}/stargazers)
[![Github Forks](https://img.shields.io/github/forks/{{ repository_name }})](https://github.com/{{ repository_name }}/network/members)
[![Github Licence](https://img.shields.io/github/license/{{ repository_name }})](https://github.com/{{repository_name }}/blob/live/LICENSE)

[![GitHub Pages Build & Deploy](https://github.com/rcpch/digital-growth-charts-react-client/actions/workflows/deploy-react-app-gh-pages.yml/badge.svg)](https://github.com/rcpch/digital-growth-charts-react-client/actions/workflows/deploy-react-app-gh-pages.yml)

:octicons-mark-github-16: [GitHub repository](https://github.com/{{ repository_name }})

:material-web: [Online Demo](https://growth.rcpch.ac.uk/)

--8<--
docs/_assets/_snippets/htn-award.md
--8<--
 

This client, written in React.js, is for demonstration of the API and the chart library component. This is now the main focus of development for our RCPCH Digital Growth Charts Demo Client. We previously built a [Flask-based client](https://github.com/rcpch/digital-growth-charts-flask-client) (which used Flask only because that client actually split off from the original API development). The Flask client code is still available as an educational tool, however it is considered deprecated and will not recieve updates.

We have attempted to build the very best of growth chart theory and practice into the React client, including guidance given to us by the RCPCH Digital Growth Charts Project Board, and accepted best practice from the days of paper growth charts.

## Clinical notes regarding the React client

### Pink and Blue no longer used for the charts

- It was felt that representing boys' charts with blue lines and girls' charts with pink lines did not really fit with 21st Century sensibilities of sex and gender. A Project Board decision was made to remove these colours and simply render the charts in monochrome black/grey, with some more off-the-wall colour themes available for variety and interest only.

## Documentation

- API documentation can be found [here](../integrator/api-reference.md) 

- If you spot errors or inconsistencies in any documentation, please do point them out to us either by creating an Issue in the relevant repository, or by making a pull request with a fix. We will [acknowledge](../about/acknowledgements) all contributors.

## Developer documentation

Built in React using Semantic UI React.

### Set Up

1. Install React [here](https://reactjs.org/docs/getting-started.html)
1. Clone the repo
1. Navigate to the root of the folder
1. `npm login --registry=https://npm.pkg.github.com` and
1. `npm install`
1. `npm start`

### Style

- We recommend the use of the Prettier Javascript linter

## Other documentation

- [Integrator documentation](../integrator/getting-started.md)
- [Contributor documentation](../developer/start-here.md)
- [Clinician documentation](../clinician/how-the-api-works.md)
