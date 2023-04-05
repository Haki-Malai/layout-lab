# layout-lab
Layout-Lab is a repository with HTML and SCSS code for creating beautiful web layouts with Flexbox.

![GitHub last commit](https://img.shields.io/github/last-commit/Haki-Malai/layout-lab)

## Installation
To install the project, simply clone the repository to your local machine:
```sh
git clone https://github.com/Haki-Malai/layout-lab.git
```

## Usage
The **index.html** file is the main entry point for the project. To view the project in your web browser, simply open the **index.html** file in your preferred browser.

The **style.css** file contains the compiled CSS for the project, while the **style.scss** file contains the Sass code that was compiled into the **style.css** file. If you wish to make changes to the styling of the project, you should make those changes in the **style.scss** file and then compile the code into CSS.

To compile the **style.scss** file into CSS, you can use a tool like node-sass or a task runner like Grunt or Gulp. Here is an example of how to use `node-sass` to compile the **style.scss** file:
```bash
npm install -g node-sass
node-sass style.scss style.css
```
This will compile the **style.scss** file into CSS and output the result to the **style.css** file.

## License
This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.
