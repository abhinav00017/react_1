PS E:\@@git\react_1> echo "# react_1" >> README.md
PS E:\@@git\react_1> git init
Reinitialized existing Git repository in E:/@@git/react_1/.git/
PS E:\@@git\react_1> git add README.md
PS E:\@@git\react_1> git commit -m "first commit"
[main (root-commit) 1fcac8c] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
PS E:\@@git\react_1> git branch -M main
PS E:\@@git\react_1> git remote add origin https://github.com/abhinav00017/react_1.git
error: remote origin already exists.
PS E:\@@git\react_1> git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 236 bytes | 236.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abhinav00017/react_1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS E:\@@git\react_1> git remote add origin https://github.com/abhinav00017/react_1.git
error: remote origin already exists.
PS E:\@@git\react_1> git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.
PS E:\@@git\react_1> npm create vite  
Need to install the following packages:
create-vite@4.4.1
Ok to proceed? (y) y
√ Project name: ... react-app_1
? Select a framework: » - Use arrow-keys. Return to submit.
>   Vanilla
    Vue
    React
    Preact
    Lit
    Svelte
√ Select a framework: » React
√ Select a variant: » TypeScript

Scaffolding project in E:\@@git\react_1\react-app_1...

Done. Now run:

  cd react-app_1
  npm install
  npm run dev

npm notice 
npm notice New minor version of npm available! 10.1.0 -> 10.2.1
npm notice Changelog: https://github.com/npm/cli/releases/tag/v10.2.1
npm notice Run npm install -g npm@10.2.1 to update!
npm notice
PS E:\@@git\react_1> cd react-app
cd : Cannot find path 'E:\@@git\react_1\react-app' because it does not exist.
At line:1 char:1
+ cd react-app
+ ~~~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (E:\@@git\react_1\react-app:String) [Set-Location], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS E:\@@git\react_1> cd react-app_1
PS E:\@@git\react_1\react-app_1> npm install

added 208 packages, and audited 209 packages in 44s

40 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
PS E:\@@git\react_1\react-app_1> npm run dev

> react-app_1@0.0.0 dev
> vite