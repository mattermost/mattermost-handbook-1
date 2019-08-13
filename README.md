# Mattermost Handbook 

This repository generates the documentation available at http://handbook.mattermost.com/.

All documentation is available under the terms of a [Creative Commons License](http://creativecommons.org/licenses/by-nc-sa/3.0/).

## WIP: Structure 

The handbook is being developed in the following rough structure: 

1. About Mattermost (`/about`) - Mission, vision, values, company, history, cadence, mindsets, metrics, definitions 
2. Contributing (`/contributors`) - contributor categories, criteria and levels: open source contributors, staff (employees + commercial contributors), partners (resellers, SIs, tech partners) 
3. Onboarding (`/onboarding`) - contributor onboarding by category, with emphasis on staff  
3. Cadences (`/cadence`) - High level processes and calendars, framed in MLT cadence for developing strategy, plan, contributors and SOPs 
6. Operations (`/sop`) - Resources and Standard Operating Procedures ("SOP") for the company aligned with strategy and plan 
4. Join Us (`/join`) - How to begin your journey of contribution and elevation 

## Technical Guide 

### Usage

To generate the HTML files from markdown in the `/source` directory:

1. Download repo onto a machine with Python installed
2. Install [pipenv](https://docs.pipenv.org/): `pip install pipenv`
3. `cd` into the cloned repository
4. Install required packages: `pipenv install`
5. Build: `make html` - generates files in `/build` directory

### Contributing

**How to create Pull Requests to edit or create Mattermost documentation (by community members):**

1. Sign the Contributor License Agreement (see instructions in the next section).
3. On the Mattermost Documentation page that you want to edit, click the GitHub icon on the upper right corner that says "Edit".
4. Click "Edit this file" (pencil icon).
5. After making changes, check the "Create a new branch for this commit and start a pull request".
6. Make sure that the Pull Request has a descriptive title. Add comments to briefly tell others what you have worked on (optional).
7. Click "Create a Pull Request".

**Signing CLA:**

Please read the [Mattermost Contributor Agreement](http://www.mattermost.org/mattermost-contributor-agreement/) and sign it (at the bottom of the page), so you can be added to the Mattermost [Approved Contributor List](https://docs.google.com/spreadsheets/d/1NTCeG-iL_VS9bFqtmHSfwETo5f-8MQ7oMDE5IUYJi_Y/pubhtml?gid=0&single=true).

**Additional process for Core Committers for Doc Repo:**

These steps are to be followed only in situations of urgency or in situations where it is necessary to check that there aren't any high confidentiality issues. Otherwise the standard approval process should be followed.

1. “Needs Editor Review” label should be processed **after merge**.
2. IMPORTANT: Person conducting editor review needs to have their suggestions **merged by author**. Do this by mentioning the pre-release.mattermost.com user name in the GitHub Pull Request.
3. Check weekly or bi-weekly that there are no “Needs Editor Review” labels on closed Pull Requests.

### Installation issues

If you can't install sphinx on MacOS try `sudo pip install sphinx sphinx-autobuild sphinx_rtd_theme --ignore-installed six`.

## Frequently Asked Questions

### Why aren't my changes reflected on handbook.mattermost.com?

1. First, wait for 15 minutes until the build finishes.
2. Search for [recent commits](https://github.com/mattermost/mattermost-handbook/commits/master) to see if one of them resulted in a build failure.
3. If there is one or more, review the changes to see if you can find a fix for it.
4. If you cannot find a fix, reach out to the R&D Infra team [in the IST Infra/Sec Team channel](https://community-release.mattermost.com/private-core/channels/infrasec-team) and ask for help. [Here's the list of current members of the Infra team](https://developers.mattermost.com/internal/rd-teams/#ops-infra-team).

### How do I create a page that appears in left sidebar navigation?

1. Identify which section you want to add the new page to, e.g. "About Mattermost".
2. Locate the file that manages the left sidebar TOC of that section, e.g. `about/about-mattermost`. The locations can be found at https://github.com/mattermost/mattermost-handbook/blob/master/source/index.rst
3. Add the new page to the TOC.

### How do I change top level folders and file names?

If you're changing folders and file names make sure to: 

1. Update the front page (6 tiles): https://github.com/mattermost/mattermost-handbook/blob/master/source/templates/index.html
2. Update the left sidebar navigation: https://github.com/mattermost/mattermost-handbook/blob/master/source/index.rst
