ts-lib-skel
===========

Typescript library skeleton project.  
<br>

Create Yarn Project
-------------------

### 1. Yarn(Classic v1) Init

Initialize 'Yarn' in the project directory.
```sh
> mkdir ts-lib-skel
> cd ts-lib-skel
> yarn init
```
> question name: `{project-name}` <code>Enter</code>  
> question version: `0.1.0` <code>Enter</code>  
> question description: `{description}` <code>Enter</code>  
> question entry point: `dist/index.js` <code>Enter</code>  
> question repository url: <code>Enter</code>  
> question author: `{name} <{email}>` <code>Enter</code>  
> question license: <code>Enter</code>  
> question private: `{Y/N}` <code>Enter</code>  

### 2. Add .gitignore

Create `.gitignore` file.
```sh
> touch .gitignore
```

Open the `.gitignore` file and add the following contents.
> `node_modules/`  
> `dist/`  

### 3. Add .npmignore

Create `.npmignore` file.
```sh
> touch .npmignore
```

Open the `.npmignore` file and add the following contents.
> `**/.*`  
> `lib/`  
> `node_modules/`  
