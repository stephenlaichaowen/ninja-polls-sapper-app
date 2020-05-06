# Ninja Polls Sapper App

## DEMO

[link](https://stephenlaichaowen.github.io/my-assets/img/ninja-polls)

## How to setup this project

Create a directory, for example `sapper-app`, and open this directory with VSCode

Clone this repo and and place under `sapper-app` directory

Change directory 
```
cd ninja-polls-sapper-app-master
```

Install all the dependencies
```
npm i
```

Start development
```
npm run dev
```

## Project Structure

src
- components
  - Header.svelte
  - Footer.svelte
  - CreatePollForm.svelte
  - PollList.svelte
    - PollDetails
  - shared
    - Button.svelte
    - Card.svelte
    - Tabs
- routes
  - index.svelte ( home page )
- store
  - createPollFormStore.js
  - PollList.js


## Upload Sapper project to Github

Create a local git repo
```
git init
```

Add all files to local repo
```
git add .
```

Commit your local git repo
```
git commit -m "your-comment"
```

Create a new repo in your Gituhb account (`github.com`)

Click `new`

Enter your Repository name and click `Create repository`

Establish remote connection on the command line
```
git remote add origin https://github.com/[your-name]/[your-repo-name].git
```

Push your local repo to your Github account
```
git push origin master
```

## Deploy Sapper App to Netlify

Login your Netlify account

Go to `app.netlify.com/teams/[your-team]/sites` page

Click `New site from Git`

Select `GitHub`  under `Continuous Deployment`

Type your repo name in `Search repos` input box or simply click the item list

Enter `npm run export` in `Build command` input box

Enter `__sapper__/export` in `Publish directory` input box

Click `Deploy site`

## Recommend Learning Resources

### Svelte Master / youtube channel
- [Svelte tutorial](https://www.youtube.com/watch?v=cU8ZPBKaEwU&list=PLcjHRSem_cvP440pjw79kB85Z_7Nn8VqZ)
- [Sapper tutorial](https://www.youtube.com/watch?v=kGfplN8HtlQ&list=PLcjHRSem_cvNDvCP3l6diqi7YBAsjfplL)
- [CSS/Component Libraries](https://www.youtube.com/watch?v=RBsNhhdPH0Q&list=PLcjHRSem_cvMiehtWg-fZiW9IbNNt9H0T)

### The Net Ninja / youtube channel
[Svelte Tutorial for Beginners](https://www.youtube.com/watch?v=zojEMeQGGHs&list=PL4cUxeGkcC9hlbrVO_2QFVqVPhlZmz7tO)

### Svelte.js Developers
[facebook](https://www.facebook.com/groups/1219388761568875)








