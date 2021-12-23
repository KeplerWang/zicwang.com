# [zicwang.com](https://zicwang.gatsbyjs.io/)(Click for preview)

## **About**

Hi, there! This is a blog repo for `zicwang.com` depolyed on [Gatsby Cloud](https://www.gatsbyjs.com/products/cloud/). 

It's built with [Gatsbyjs 4.2](https://www.gatsbyjs.com/) and inspired by [hoodie](https://github.com/devHudi)(thank this nice guy for wonderful blog template).

## **What contribution did I offer**

Simply, I just updated the Gatsbyjs plugin versions(to 4.2) and dependencies in [`package.json`](https://github.com/KeplerWang/zicwang.com/blob/main/package.json), and fixed some errors by checking [`gatsby-config.js`](https://github.com/KeplerWang/zicwang.com/blob/main/gatsby-config.js) and some JavaScript files due to the updates.

## **How to reproduce this blog**

You can reroduce this repo through following steps.

### **1. Set Up Your Development Environment(Node.js, Git, etc)**
You can follow this [site](https://www.gatsbyjs.com/docs/tutorial/part-0/).
### **2. New a Gatsby Site**
   
This allows you to clone this repo and install gatsbyjs plugins and dependencies automatically.
```bash
npm gatsby new {Your Gatsby Site Name} https://github.com/KeplerWang/zicwang.com
```
If it doesn't work like throwing errors, you can try this.
```bash
git clone https://github.com/KeplerWang/zicwang.com
cd {Git Repo Folder}
npm install --legacy-peer-deps
```

### **3. Start sever and preview**
```bash
cd {Git Repo Folder} # If you're already there, pass this line.
gatsby develop
```

### **4. Set up a GitHub repo for your site**
```bash
git remote add origin https://github.com/{Your Github Username}/{Your Git Repo Folder}.git
git add .
git commit -m 'First Commit'
git branch -M main
git push -u origin main
```

### **5. Deploy on Gatsby Cloud**
It's easy to delopy on [Gatsby Cloud](https://www.gatsbyjs.com/dashboard/login) if you upload your repo to Github. Just click the mouse :D.

## **Enjoy**
