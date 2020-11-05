## Setup
**Install http-server**

_npm install -g http-server_

We want to make our website as lightweight as possible and therefore
we should only use necessary libraries/packages.

We will have to remove unused css, javascript, scrippts and svg files but we
can do that at the end.

For now you can use `http-server`, which is installed globally, to start a 
server in any directory and go to localhost:8080 on the browser to look at the
contents of the directory.

## Contents
**assets**: Taken everythings from Front. _Need to be cleaned later._

**snippets**: Taken everything from Front. _Need to be cleaned later._

**html**: Removed everything except the directory structure as html pages are
using relative paths to find css, javascript, etc. 

Renamed `html/landings/onepage-saas.html` to `html/landing/index.html`.
Added placeholder holder files for other pages that we will need in `html/pages`.

## Test changes
1. Install `http-server`.
2. Go to `./something-ops` directory.
3. Run HTTP server by command `http-server`.
4. Open http://localhost:8080 in browser.

## Some useful git commands
**git clone [url]**
retrieve an entire repository from a hosted location via URL.

**git pull**
fetch and merge any commits from the tracking remote branch.

**git add [file/directory]**
add a file/directory as it looks now to your next commit (stage).

**git commit**
commit your staged content as a new commit snapshot.

**git push**
transmit local branch commits to the remote repository branch.

[Git Command Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

[Git Simple Guide](https://rogerdudler.github.io/git-guide/)
