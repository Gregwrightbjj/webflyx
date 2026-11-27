# Webflyx - Boot.dev Git Practice

Webflyx is a practice repository created while working through Boot.dev's
Learn Git course. It uses a fictional movie collection as sample content for
learning how to track changes and collaborate with Git and GitHub.

This repository contains text documents, movie quotes, and a CSV of classic
movies. It is a learning exercise, not a working streaming service or an
application that needs to be installed or run.

## What I practiced

- Recording changes with commits and inspecting their history.
- Creating branches to work on separate changes.
- Merging branches and bringing remote changes into a local repository.
- Opening and merging GitHub pull requests.
- Using a `.gitignore` file to control which untracked files Git ignores.

The commit history and merged pull requests are part of the exercise: they
show how the sample content changed as I practiced these workflows.

## Files in this repository

| File or folder | What it contains |
| --- | --- |
| `README.md` | This explanation of the project and its purpose. |
| `contents.md` | An index of the movie-collection files. |
| `titles.md` | Sample movie titles. |
| `classics.csv` | A comma-separated list of classic movies. |
| `quotes/` | Text files with quotes from Dune and Star Wars. |
| `advert.md` | A fictional Webflyx advertisement used as practice content. |
| `.gitignore` | Rules for files Git should leave untracked. |

## How to explore it

Browse the files, commit history, and merged pull requests on GitHub. To
inspect the history locally, clone the repository and view the commit graph:

```bash
git clone https://github.com/Gregwrightbjj/webflyx.git
cd webflyx
git log --oneline --graph --all --decorate
```

The value of this project is the Git practice and development history; the
movie content gives those exercises something concrete to change.
