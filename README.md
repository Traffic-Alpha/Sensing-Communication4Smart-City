<!--
 * @Author: WANG Maonan
 * @Date: 2024-06-04 00:09:09
 * @Description: README for Website
 * @LastEditTime: 2024-07-28 00:52:28
-->
# Laboratory of Sensing and Communication for Smart City

This repository contains the website for the **Laboratory of Sensing and Communication for Smart City**.

## Installation

To modify the website content, you need to install the MkDocs with the Material theme. Install it using pip:

```bash
pip install mkdocs-material
```

## Running the Website Locally

To view and edit the website content in real-time, navigate to the project directory and run the following command:

```bash
mkdocs serve
```

This command starts a local web server that hosts the website. Any changes you make to the documentation source files will automatically rebuild the site and refresh the page in the browser.

## How to Submit Changes

First, update the repository to ensure you have the latest data:

```bash
git pull
```

Then, stage your changes and provide a descriptive commit message:

```bash
git add .
git commit -m "Describe the changes here"
```

Finally, push your changes to the repository:

```bash
git push
```

## File Structure

Below is a brief overview of the key files and directories in this repository:

- `mkdocs.yml`: The configuration file for the MkDocs project. This file includes settings for the MkDocs build and the plugins used for the website.
- `docs/`: Directory containing the Markdown files for the website's content. Each file corresponds to a page on the website.
  - `index.md`: The homepage document.
  - `pubs.md`: Contains information about published papers.
  - `members.md`: Introductions to the project members.