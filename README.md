# GitHub User Creation Date Viewer

## Overview

This is a simple Bootstrap-based web app that lets users input a GitHub username and optionally a personal access token to fetch and display the GitHub account creation date in UTC (`YYYY-MM-DD` format). The form with ID `github-user-696969` fetches the details from the GitHub API and outputs the creation date inside the element with ID `github-created-at`.

## Setup

No special setup is needed. It is a static HTML page using Bootstrap 5 from CDN and standard Fetch API.

## Usage

1. Open the `index.html` in any modern web browser.
2. Enter a valid GitHub username.
3. Optionally enter a GitHub personal access token in the token field if you want to increase API rate limits.
4. Press **Fetch Creation Date**.
5. The account creation date (UTC) will be displayed below the form.

## License

MIT License