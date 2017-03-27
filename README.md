# TIL
Today I learned 

  *  Project names change 
Specially for MVPs, the name chosen at the beginning of the project will probably change even before launching. We can use a nickname for the project, so that the name used in the settings, and environment names doesn't have to be affected after the possible name change. 

  *  Make sure event date is correct before ordering food
Imagine you order food, but you find out the event is actually tomorrow.

  *  Make your Twitter etc. focused on one thing

  *  pgAdmin 4 can be run using docker, no other installation needed 
TODO add the command

  *  pgweb is a good GUI for postgress, but still doesn't let you edit values
https://github.com/sosedoff/pgweb/releases/tag/v0.9.6

  *  Whatever chat system your team uses, you go there becuase of the people not the software, have fun, don't worry much.

  *  yargs is a nice NPM package to make CLI tools with nodejs

  *  Inspecting the tldr package on NPM, shows they use commander a dead simple cli package, and chack for coloring it, and the content is in markdown files on home directory of the user

  *  There's a nice set of react patterns ([link](http://reactpatterns.com/#state-hoisting)), that has good examples, more clear than the docs in some cases.
  This one explains state hoisting or how to put a text input inside a stateless function:
  ```javascript
  class NameContainer extends React.Component {
  render() {
    return <Name onChange={newName => alert(newName)} />
  }
}

const Name = ({ onChange }) =>
  <input onChange={e => onChange(e.target.value)} />
``` 

  *  there's this nice webpack setting generator for webpack / project setup https://github.com/linuxenko/unstuck-webpack 
  *  you can register foo.js.org for javascript projects
  
  *  There are many (PWA) progressive web apps currently in prodcution and many of libraries they use are open source and here's a good article on it by Addy Osmani ([link](Nice article summarizing many libraries in production https://medium.com/dev-channel/progressive-web-app-libraries-in-production-b52cad37d34#.7p9rf5gm7)) 

  *  About pros and cons of reuse: http://blog.jessitron.com/2017/02/reuse.html

  *  you can inspect AVA tests, or any nodejs program in chrome dev tools just like normal javascript on pages very smoothly using [inspector](https://github.com/jaridmargolin/inspect-process)

  *  this library wraps native modules of nodejs like fs in promises, like modernizer for node [mz link](https://github.com/normalize/mz)

  *  this package is great for publishing to npm [np link](https://github.com/sindresorhus/np)
  *  list of cool node js stuff, including great CLI tools [awesome nodejs link](https://github.com/sindresorhus/awesome-nodejs#command-line-apps)
  *  you can get random cows in command line [link](https://www.npmjs.com/package/cows)
  *  nvm can migrate all global packages while installing a new version on nodejs [link](https://github.com/creationix/nvm#migrating-global-packages-while-installing)
  *  aspell can check spelling in command line. 
```bash
aspell check file.txt 

# get all typos in a file
aspell list < document.txt 

# to check multiple files
find *.txt -exec aspell check {} \;
```
  *  [Node Green](https://node.green) has a full list of all ES6 features by version 
  *  npm install -g covgen and then covgen <your email address> creates a code of contact! 
  *  create an automatic forward list of emails emaillist.io [(link)](https://emaillist.io)
  *  Meow can be used for making CLI tools like magic [(link)](https://github.com/sindresorhus/is-up-cli/blob/master/cli.js)
  *  Animista can generate css animations by point and clicking [(link)](http://animista.net/)
  *  an http wrapper for postgres written in haskel Putting a translator in front of postgres [(link)](https://github.com/begriffs/postgrest)
  
  * add ip manually to jail in fail2ban 
  ```bash
  sudo fail2ban-client -vvv set sshd banip 202.109.0.0/16
  
  # Check the jail where to add the IP using sudo fail2ban-client status
  ```

