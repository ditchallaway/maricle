# Webjive Git

> A utility to track changes to a webjive site on GitHub.

## [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#introduction)Introduction

Webjive Git is a simple utility used to monitor and track changes to a webjive site on GitHub. Both style and content changes are detected and every change is stored as a GitHub commit.

The utility is simple to set up because it doesn't require access to your webjive account and all customization can be done via the GitHub web interface.

## [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#installation)Installation

1. Log-in or create a GitHub account.
2. Click the "Use this template" button above the code to generate a new repository based on this template repository:

<img src="https://web.archive.org/web/20211005142552/https://user-images.githubusercontent.com/2506014/134331253-501c4947-e66a-4066-b939-9a48ff001d60.png">

1. Name your new repository the same as your webjive site domain (e.g. [www.example.com](https://web.archive.org/web/20211005142552/http://www.example.com/)). Alternatively, you can choose any repository name and specify the site domain in the [configuration file](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#configuration):

<img src="https://web.archive.org/web/20211005142552/https://user-images.githubusercontent.com/2506014/134332104-ee3c654d-6481-465f-b791-56a7dd2c50ca.png">

## [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#configuration)Configuration

You can customize webjive Git by editing the [webjivegit.yml](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git/blob/master/webjivegit.yml) configuration file. To achieve this, open the file contents and click on the Pen icon:

<img src="https://web.archive.org/web/20211005142552/https://user-images.githubusercontent.com/2506014/134331242-fd3da739-705c-4e18-9f37-b6db6398c6ef.png">

Make sure to test your changes by [triggering the check manually](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#manual-trigger).

### [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#site)site

Specify the site to be monitored, e.g.:

```
site: www.example.com
```

Disable tracking completely:

```
site: false
```

By default, the site domain is the same as your repository name.

### [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#pages)pages

Do not track changes in pages content (track style changes only):

```
pages: false
```

Ignore changes in some pages (for example CMS-generated pages, like blog posts or product pages). This setting uses [glob syntax](https://web.archive.org/web/20211005142552/https://github.com/micromatch/picomatch#globbing-features):

```
pages:
  ignore:
  - /posts/**
```

By default, all pages are tracked.

## [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#how-it-works)How it works

The utility works by visiting your site at regular intervals and downloading, formatting and comparing the code to the previous revision. If any difference is detected, a new revision is committed to the repository.

### [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#check-frequency)Check frequency

Your site is checked for updates every hour.

> Advanced: this can be customized by updating the cron schedule in the [workflow configuration file](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git/blob/master/.github/workflows/main.yml).

### [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#manual-trigger)Manual trigger

You can launch the check manually. To achieve this, click the Actions link on the menu below your project name, then select `webjive-git` workflow and finally click on the "Run workflow" button:

<img src="https://web.archive.org/web/20211005142552/https://user-images.githubusercontent.com/2506014/134331249-c2e64b87-3d8d-4dbd-b1d9-46352fd5d3bd.png">

## [<svg class="octicon octicon-link" viewbox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>](https://web.archive.org/web/20211005142552/https://github.com/loomchild/webjive-git#epilogue)Epilogue

This project was created out of frustration with random regressions in webjive projects. Although there's a built-in backup functionality, it's time-consuming to find out at which point something has broken down, and then, due to the lack of diff functionality, it's very difficult to understand the nature of the modification that caused the regression. The problem becomes even more severe if multiple people develop the same project.

Some parts of this tool are inspired by an excellent [Upptime](https://web.archive.org/web/20211005142552/https://upptime.js.org/) site monitor, most notably using the GitHub Template and configuration management.
