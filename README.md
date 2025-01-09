# NF-Ridoy-Git-Methodology
## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
   - [Installation 111: Alternative GitHub Repository (Time-Saving)](#installation-111-alternative-github-repository-time-saving)
   - [Installation 101](#installation-101)
3. [Branching Strategy](#branching-strategy)
   - [2025 Branches](#2025-branches)
   - [2023 Branches](#2023-branches)
4. [Forking a Repository](#forking-a-repository)
5. [Working with Markdown](#working-with-markdown)
6. [Changing Git Remote Origin](#changing-git-remote-origin)
7. [npm Knowledge](#npm-knowledge)
8. [Using nodemon to Run Server](#using-nodemon-to-run-server)
9. [References](#references)

---

## Introduction
This is the Git repository for NF-Ridoy Git Development Methodology.

---

# Installation 111
## Alternative Github Repository [Time Saving]
~~~
Create a GitHub Repository
Must ADD .gitignore
Finish it.
COPY the HTTP URL
git clone it using the URL link
~~~
## Installation 101
## 0.0 Must ADD .gitignore
PRESS F1 > SEARCH add gitignore > TYPE/SELECT node
## Make 4 main branches [2025]:
### main(public/deploy), develop, stage, backup, deploy(if its serious project)
1. main : (public/deploy branch) : parent -> stage
2. develop : main coding branch
3. stage : parant -> develop
4. backup : parant -> develop
5. deploy : use dedicated deploy for serious project

### Make 9 branches [2023]: main, main-structure, develop, Responsive, Alpha, gh-pages, Beta, Gamma, Delta
### 1. Branch Details:
<br> **main:** Main Master::  >> Merge main to gh-pages.
<br> **main-structure:** Main Structure :: Merge main-structure to develop // [Merge main-structure to main]
<br> **develop:** || Merge develop to Responsive
<br> **Responsive:** Merge Responsive to Alpha
<br> **Alpha:** Merge to main && Merge to Beta.
<br> **gh-pages:** For Live Server/Link
<br> **Beta:** Merge to Gamma.
<br> **Gamma:**
<br> **Delta:**
<br> ---------------------------------------------------- <br>
### 2. Branch Serial:
main >> main-structure >> develop >> Responsive >> Alpha >> Beta >> Gamma >> Delta
<hr>



# Fork A Repository
How To Fork A Repo <br>

```c
git clone <HTTP Link> 
git add . 
git commit -m "New Update" 
git push
```

#### Always "git clone" is Better than "Download zip" For everything (fork, clone, setup on another PC) 

<br> ---------------------------------------------------- <br>

## How to Code in .md

\```Programming Name <br>
Your Code <br>
\``` <br>
your can also use three ~ <br>

### For Example: 
\```javascript <br>
let a = 5; <br>
\``` <br>

## Change Existing Remote Origin using git remote set-url.txt
~~~
git remote set-url <URL>
~~~
OR
```
git remote remove origin
git remote add origin <URL>
```

## npm Knowledge 
~~~
npm init -y 
~~~
Here -y means Yes all

## nodemon To run server
~~~
nodemon index.js
~~~
## Remove Git Remote Origin
<a href="https://chat.openai.com/share/f555f2b0-3c9e-4eca-a0e6-47310a10ec4e">How TO</a>

<!-- ## Usage
This is the git repository for NF-Ridoy Git Development Methodology.
## Contributing
This is the git repository for NF-Ridoy Git Development Methodology.
## Tests
This is the git repository for NF-Ridoy Git Development Methodology.
## Questions
This is the git repository for NF-Ridoy Git Development Methodology.
## License
This is the git repository for NF-Ridoy Git Development Methodology.
## Contact
My Email: nfridoy@gmail.com
## Credits
This is the git repository for NF-Ridoy Git Development Methodology.
## Badges
This is the git repository for NF-Ridoy Git Development Methodology.
## Features
This is the git repository for NF-Ridoy Git Development Methodology. -->
