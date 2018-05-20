# Julianna Garreffa Resume
🎉🎈🎂🍾🎊🍻💃

*Simple HTML page for wrapping resume embed item from Google Drive*

## Motivation

This technique makes it easy to maintain an up to date version of a resume (or some other form of embeddable google document) available online.

## How to Use

0. Fork this repo, make sure to update the title **[here](https://github.com/jgarreffa112/resume/blob/master/index.html#L4)**.
1. Create a Google Drive document that is publicly viewable
2. Following this **[tutorial](http://www.alicekeeler.com/2016/06/05/google-drive-embed-pdf/)**, copy and store (for now) the embed code.
3. Update **[this line](https://github.com/jgarreffa112/resume/blob/master/index.html#L15)** with the embed code copied in **2**.
4. Deploy to **[Github Pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages)**

## Updating Doc subsequently

For subsequent doc updates, code changes are **not** needed! Navigate to the doc in Drive and right click, choosing **Manage versions...**.

![step1](https://github.com/jgarreffa112/resume/blob/master/screenshots/step1.png?raw=true)

Then, from the popup that shows up, upload new doc by clicking **Upload New Version**.

![step2](https://github.com/jgarreffa112/resume/blob/master/screenshots/step2.png?raw=true)

This is required to ensure that the ID of the item embedded stays constant, rendering any _code_ changes unnecessary.
