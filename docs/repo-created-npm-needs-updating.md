I've created a repo at ____. Please update your npm package with the new issues and bump the version. I've created a team that has admin rights to this repo so you can control it as you see fit.

Here are some steps to help you get started.
Clone the new repository:

`git clone <new repo>` OR `git remote set-url origin <new repo>`

Make the following edits to package.json:
* update repository:url
* update bugs:url

Then run the following commands:

```
npm version patch
npm publish
git push origin master
```

After that, please delete your old repository, close this ticket, and :metal: rock on.
