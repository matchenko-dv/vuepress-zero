# VuePress

It **only** takes one **README.md** file to create and deploy a VuePress site. 
The simplicity of this high quality documentation system is the beauty of VuePress. 


It’s also possible to ``vuepress eject`` and get a fully blown Vue site that compiles in components and works offline.  

Generate an [Initial VuePress Site](https://vuepress.vuejs.org/guide/getting-started.html#global-installation) official documentation.  

### Step 1 
 
::: warning  COMPATIBILITY NOTE
VuePress requires Node.js >= 8 and npm >= 5.2
:::  

|&nbsp;[Download Node.js and npm](https://nodejs.org/en/) &nbsp;|&nbsp;&nbsp; [Read the docs!](https://www.npmjs.com/get-npm)|  

To check if you have Node.js installed, run this command in your terminal:

``node -v``  

To confirm that you have npm installed you can run this command in your terminal:

``npm -v``  


### Step 2  



```bash 
# Create the project folder
mkdir vuepress && cd vuepress  

# Create a README.md file with markdown formatted content
echo # VuePress > README.md

# Install VuePress temporary for this node process only with development server
npx vuepress dev  

# Open in a browser
open http://localhost:8080
```  

With this **README.md** file and the installation of the **VuePress** package, you have a professional 
layout out of the box with this features. 

- Responsive layout
- Optional Homepage
- Simple out-of-the-box header-based search
- Algolia Search
- Customizable navbar and sidebar
- Auto-generated GitHub link and page edit links  


### Result  
**README.md** file with one line markdown code  

``# VuePress ``
  
gives you this responsive layout with header, search box and menu icon out of the box.

<img src="http://res.cloudinary.com/iicamp/image/upload/v1530689700/VuePress/Group_1_2x.png" />
	 
Each markdown file is compiled into HTML with **markdown-it** and then processed as the template of a Vue component. This allows you to directly use Vue inside your markdown files and is great when you need to embed dynamic content.  

VuePress compiles ``README.md`` files using **markdown-it**. You can find the markdown-it syntax in this demo
	
[Markdown-it demo](https://markdown-it.github.io/)  


### Additional Features of VuePress are  

- Built-in markdown extensions optimized for technical documentation  
- Ability to leverage Vue inside markdown files  
- Vue-powered custom theme system  
- Automatic Service Worker generation  
- Google Analytics Integration  
- "Last Updated" based on Git  
- Multi-language support  

### Step 3  
#### Built-in markdown extensions optimized for technical documentation  

#### Config Reference
#### ``markdown.toc``
- Type: ``Object``    
- Default: ``{ includeLevel: [2, 3] }``    

Options for [markdown-it-table-of-contents](https://github.com/Oktavilla/markdown-it-table-of-contents). 
(Note: prefer ``markdown.slugify`` if you want to customize header ids.)  

All headers with Level 2 (##) and Level 3 (###) will go into TOC. This can be customized.

```bash  
# Table of Contents

[[toc]]

## What is Lorem Ipsum?
Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
Lorem Ipsum has ...

## Why do we use it?
It is a long established fact that a reader will be distracted by the readable content 
of a page when looking ...

### Where does it come from?
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece 
of classical Latin literature...

## The standard chunk of Lorem Ipsum 
used since the 1500s is reproduced below for those interested. 
Sections 1.10.32 and 1.10.33 from "de Finibus...

### Where can I get some?
There are many variations of passages of Lorem Ipsum available, but the majority have
suffered alteration in some form, by injected humour,...
```  

### Result
<img src="http://res.cloudinary.com/iicamp/image/upload/v1530788601/VuePress/toc-04.png" />  

### Tips and Tricks:  

If you need the latest npm installed

```bash
npm install npm@latest -g
```
 

::: tip
*It is currently recommended to use Yarn instead of npm when installing VuePress into an **existing project** that has webpack 3.x as a dependency. Npm fails to generate the correct dependency tree in this case.*
:::  

You can check, if **Node**, **Yarn** and **Vuepress** is already installed: 
```bash
$ node --version  
$ yarn --version  
$ vuepress --version
```  
```bash
$ node -v  
v8.11.3
```  
If you see a version number on your screen then the software is installed.  
Otherwise you need to download and install it.  

## Installing Node, Yarn and VuePress  
[Node Installation](https://nodejs.org/en/download/)  
[Yarn Installation](https://yarnpkg.com/lang/en/docs/install/#windows-stable)  
[VuePress Installation](https://www.npmjs.com/package/vuepress )  


## Updating Node, Yarn and VuePress  
[Node Update](https://nodejs.org/en/)  
[Yarn Update](https://yarnpkg.com/en/docs/cli/upgrade)  
[VuePress Update](https://www.npmjs.com/package/vuepress)  


```bash
nvm install 8.1.0 (any version number - nvm = Node Version Manager)
yarn upgrade --latest
yarn global add vuepress # OR npm install -g vuepress
```  









