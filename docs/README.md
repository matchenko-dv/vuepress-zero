# LIVING & GOOD COMMUNICATION IS HARD
- - -
Documentation can be difficult, but it's the key to any project's long term success.

# VuePress  


> Minimalistic docs generator with Vue component based layout system  
  
The simplicity of this high quality doc system is the beauty of **VuePress**.  

<br />  


### Environment Setup

::: tip COMPATIBILITY NOTE
VuePress requires Node.js >= 8
:::
 
**VuePress** is a **Node** application that needs to be installed via **NPM** or **Yarn**.

You can use NPM (Node Package Manager) or Yarn to install VuePress within either a new or existing project. 

To check you have **Node.js** installed along with access to **NPM**, open up your console and type:  

| `node -v` | **and** | `npm -v` |  

Both of these commands should provide you with version numbers. If they go unrecognized, visit [Node.js](https://nodejs.org/en/) 
and download the appropriate installer based on your operating system. Install it through the default options and reload your console.
[Read the docs for upgrading to >=8](https://www.npmjs.com/get-npm), if needed.  

You can now re-issue the same commands and they will work. 

The same is valid for yarn  

| `yarn -v` |

| [Download Yarn](https://yarnpkg.com/lang/en/docs/install/#windows-stable) |   


Optional:  
[Download Git](https://git-scm.com/downloads) for later use of Github, GitLab or Bitbucket  
Use an editor you like, for example [Visual Studio Code](https://code.visualstudio.com/download)  

<br />  



## Installing VuePress  
 

```bash
npm install -g vuepress  | or | yarn global add vuepress
``` 

#### Create the project folder

```bash

mkdir myProject && cd myProject  
```  

#### Create a README markdown file with **'# Hello VuePress'**

```bash
echo '# Hello VuePress' > README.md
```  

#### Start Server
```bash  
vuepress dev  
``` 

#### Open in a browser  
```bash
http://localhost:8080
```

With the installation of **VuePress** and a **README.md** file, you have a `professional layout out of the box` with the following features.

- Responsive layout
- Optional Homepage
- Simple out-of-the-box header-based search
- Algolia Search
- Customizable navbar and sidebar
- Auto-generated GitHub link and page edit links

### Result

**README.md** file with one line of markdown content `# VuePress`
gives you this responsive layout `header`, `search box` and `menu icon` out of the box.

<img src="http://res.cloudinary.com/iicamp/image/upload/v1530689700/VuePress/Group_1_2x.png" />

Each markdown file is compiled into HTML with **markdown-it** and then processed as the template of a Vue component. This allows you to directly use Vue inside your markdown files and is great when you need to embed dynamic content.

VuePress compiles `README.md` files using **markdown-it**. You can find the markdown-it syntax in this demo
[Markdown-it demo](https://markdown-it.github.io/)

### Additional Features of VuePress are

- Built-in markdown extensions optimized for technical documentation
- Ability to leverage Vue inside markdown files
- Vue-powered custom theme system
- Automatic Service Worker generation
- Google Analytics Integration
- "Last Updated" based on Git
- Multi-language support


### Tips and Tricks:

If you need the latest npm installed

```bash
npm install npm@latest -g
```


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
[VuePress Installation](https://www.npmjs.com/package/vuepress)

## Updating Node, Yarn and VuePress

[Node Update](https://nodejs.org/en/)  
[Yarn Update](https://yarnpkg.com/en/docs/cli/upgrade)  
[VuePress Update](https://www.npmjs.com/package/vuepress)

```bash
nvm install 8.1.0 (any version number possible - nvm = Node Version Manager)
yarn upgrade --latest
```
