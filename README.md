# TIL
Today I learned 

1. Project names change 
Specially for MVPs, the name chosen at the beginning of the project will probably change even before launching. We can use a nickname for the project, so that the name used in the settings, and environment names doesn't have to be affected after the possible name change. 

1. Make sure event date is correct before ordering food
Imagine you order food, but you find out the event is actually tomorrow.

1. Make your Twitter etc. focused on one thing

1. pgAdmin 4 can be run using docker, no other installation needed 
TODO add the command

1. pgweb is a good GUI for postgress, but still doesn't let you edit values
https://github.com/sosedoff/pgweb/releases/tag/v0.9.6

1. Whatever chat system your team uses, you go there becuase of the people not the software, have fun, don't worry much.

1. yargs is a nice NPM package to make CLI tools with nodejs

1. Inspecting the tldr package on NPM, shows they use commander a dead simple cli package, and chack for coloring it, and the content is in markdown files on home directory of the user

1. There's a nice set of react patterns ([link](http://reactpatterns.com/#state-hoisting)), that has good examples, more clear than the docs in some cases.
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
  
1. There are many (PWA) progressive web apps currently in prodcution and many of libraries they use are open source and here's a good article on it by Addy Osmani ([link](Nice article summarizing many libraries in production https://medium.com/dev-channel/progressive-web-app-libraries-in-production-b52cad37d34#.7p9rf5gm7)) 

1. About pros and cons of reuse: http://blog.jessitron.com/2017/02/reuse.html

1. you can inspect AVA tests, or any nodejs program in chrome dev tools just like normal javascript on pages very smoothly using [inspector](https://github.com/jaridmargolin/inspect-process)

1. this library wraps native modules of nodejs like fs in promises, like modernizer for node [mz link](https://github.com/normalize/mz)

1. this package is great for publishing to npm [np link](https://github.com/sindresorhus/np)
