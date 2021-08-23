# retirement-template

Template for data for the retirement simulator. This provides an initial set of .csv files you can edit with any
spreadsheet editor (or text editor if you're careful and know what you're doing).

<!-- markdownlint-disable MD036 -->
__WARNING: DO NOT PUSH YOUR PRIVATE DATA TO A PUBLIC REPOSITORY__
<!-- markdownlint-enable MD036 -->

If you cloned this repo with git, it is best to remove the `origin` remote, as any updates
to the template are unlikely to apply well to this reposititory after you supply your data.

Using git locally is still a good idea, to allow you to find and fix mistakes, etc. You can even push to
a git server or file copy so long as you are certain of the security of the destination.

```bash
git remote remove origin
````

## Prerequisites

* Node, available from [nodejs.org](https://nodejs.org)
* npm, installed with Node
* A spreadsheet program to edit the data

## Setup

You can clone this repo with:

```bash
git clone https://github.com/BobKerns/retirement-template.git my-retirement-data
cd my-retirement-data
git remote remove origin
npm install
```

## Operation

To make this data availale to web pages running locally, from the command line, go to the my-directory-data directory and type 'npm run serve'

## The data

The data is in the [/data/](/data) subdirectory.

## Note

The source for this file is [README.md](README.md), using [Github-flavored Markdown syntax](https://github.github.com/gfm/). You can read the spec, or just imitate what appears here for basic stuff.

If you make changes to this file, you will need to re-run the `npm run serve` command for the changes to appear.
