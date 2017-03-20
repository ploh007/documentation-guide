# Documentation Guide for Personal Projects
Compiled by [Paul Loh](http://paulloh.com) 2017

## Graphic Design Projects

### General Guidelines
* Store in .psd file format
* Export for upload / circulation in .jpeg for best compression format 
* Use generic dimensions to ensure appropriate scaling of content/media
* Keep content in groups where applicable and name layers meaningfully

### Print Development
* Use CMYK color scheme for accurate printing representation

### Mockups / Digital Print 
* Use RGB color scheme for best representation of media accuracy

## PHP Web Development Projects
* Attempt to use a framework where applicable
* Usage of Model-View-Controller Design Pattern
* Ensure that code is well formatted, documented and bugs/issues are tracked appropriately
* Keep a test plan in sync with code functionality and development
* Use [Composer](https://getcomposer.org/) for application package management
	* Basic Commands
		* `composer install` - installs project dependencies from composer.json 
		* `composer update` - updates all project dependencies to latest version along with composer.json and composer.lock
		* `composer validate` - validates the project composer.json and composer.lock
		* `composer show` - shows the project packages information
		* `composer require <package-name>` - adds required package to composer.json and installs them
		* `composer remove <package-name>` - removes the package from the composer.json 

## Electron Application Development Projects
* Use frameworks which allow cross-platform deployment of applications
* Use [NPM](https://getcomposer.org/) for application package management
	* Basic Commands
		* `npm install <package-name>` - installs node package to application folder
		* `npm install <package-name> -g` - installs node package globally for all applications
		* `npm uninstall <package-name>` - uninstalls node package
		* `npm update` - updates all project dependencies to latest version
		* `npm prune` - Cleans up unreferenced packages

## Git Source Version Control
* Use [Git](https://git-scm.com/) for source version control for any project/development

## Licensing
* Ensure that licensing information is included along with projects and that appropriate attribution is included where applicable 
* Most licensing information is to be licensed under MIT License 
* Follow the following quoted text block for licensing information

>Copyright 2017 Paul Loh
>
>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.