# NPM Examples

I believe `package.json` has all the dependencies we use for UndocuScholar Web.

## Using NPM

1. Install [npm](https://docs.npmjs.com/getting-started/installing-node).
2. The `npm` command should work on your terminal/Git Bash.
3. Clone this repo somewhere. (Possibly your desktop)
4. Open your terminal and `cd` into this repo.
5. Type `npm install`.

A folder `node_modules` has been created. Voila, that's how we manage dependencies on third party libraries. All we need to do in the main repo is have the package.json file and then from the app's end associate the path with static files and use that path in the HTML templates we write. This way we don't `git add` all these dependencies into our repo, cluttering our files.