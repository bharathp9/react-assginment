Quick Start
-----------
```bash
create-react-app new-app

cd new-app

npm start
```


```bash
Bharath Kumar@OmSaiRam MINGW64 ~
$ cd Desktop/Training/new-app

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app
$ git init
Initialized empty Git repository in C:/Users/Bharath/Desktop/Training/new-app/.git/

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (master)
$ git add .
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in public/index.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in public/manifest.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/App.css.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/App.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/App.test.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/index.css.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/index.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/logo.svg.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in src/registerServiceWorker.js.
The file will have its original line endings in your working directory

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (master)
$ git commint -m"original version"
git: 'commint' is not a git command. See 'git --help'.

The most similar command is
        commit

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (master)
$ git commit -m"original version"
[master (root-commit) 985ca7c] original version
 14 files changed, 9864 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 package.json
 create mode 100644 public/favicon.ico
 create mode 100644 public/index.html
 create mode 100644 public/manifest.json
 create mode 100644 src/App.css
 create mode 100644 src/App.js
 create mode 100644 src/App.test.js
 create mode 100644 src/index.css
 create mode 100644 src/index.js
 create mode 100644 src/logo.svg
 create mode 100644 src/registerServiceWorker.js
 create mode 100644 yarn.lock

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (master)
$ git checkout -b step1
Switched to a new branch 'step1'

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step1)
$ git branch
  master
* step1

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step1)
$ git diff --name-only
warning: LF will be replaced by CRLF in src/index.js.
The file will have its original line endings in your working directory
src/index.js

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step1)
$ git add .
warning: LF will be replaced by CRLF in src/index.js.
The file will have its original line endings in your working directory

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step1)
$ git commit -m"step1: done todoApp frpm reactjs.org"
[step1 3e7109a] step1: done todoApp frpm reactjs.org
 3 files changed, 140 insertions(+), 1 deletion(-)
 create mode 100644 log to followup.txt
 create mode 100644 src/step1/App.js

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step1)
$

$ git checkout -b step2
Switched to a new branch 'step2'
M       log to followup.txt

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step2)
$ git branch
  master
  step1
* step2

Bharath Kumar@OmSaiRam MINGW64 ~/Desktop/Training/new-app (step2)
$

```