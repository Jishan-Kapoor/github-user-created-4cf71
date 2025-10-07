# GitHub User Info Web App

## Summary
This static web application allows users to input a GitHub username, fetch the account creation date, and display it in UTC format on the page.

## Setup
To deploy on GitHub Pages:
1. Create a new repository on GitHub.
2. Push your code, including the Bootstrap page, to the repository.
3. Enable GitHub Pages under settings and choose the main branch as the source.

## Usage
- Access the web page via the deployed GitHub Pages link.
- Optionally use the `?token=` query parameter to authenticate GitHub API requests.
- Enter a GitHub username in the form field with id="github-user-24f100364@ds.study.iitm.ac.in-2025-10-07-11" and view the account creation date displayed inside #github-created-at.

## Code Explanation
The HTML page includes a form element with the specified id to fetch the GitHub username input. JavaScript is used to interact with the GitHub API and display the account creation date in the designated #github-created-at element.

Libraries: None
Algorithms/Logic: Fetch GitHub API, extract creation date, and display in UTC format.

## License
This project is licensed under the MIT License.