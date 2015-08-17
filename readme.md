# Read me.

Before we start doing this, you're going to need to equip your computer with some fancy pants tech. So, here's a shopping list of what you'll need.

- Ruby - You should already have ruby installed, type `ruby -v` into terminal to find out. If you don't, install Xcode or google `Install ruby on osx`
- Git - Installed with xcode, but if you don't have xcode, download here: [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Node.js - Installer here: [https://nodejs.org/download/](https://nodejs.org/download/)
- Grunt.js - past this into terminal `npm install -g grunt-cli`
- Sass - Past this into your terminal: `sudo gem install sass`
- MAMP or Vagrant. MAMP is 100% easier than figuring out VAGRANT, but vagrant can be a clone of the server online.

Now you have all these things, you're a developer! Welcome to a life of matrix style windows and frustration that something so simple isn't working.

## How to run this project

With most projects, they will contain two files. 

- package.json
- gruntfile.js

These two files are the absolute everything. They will install everything you need for this project and will set you up to have a working environment.

To be able to compile your code, sass and other cool features, open terminal and type: `cd ` then type the path to your folder. 

Now, if you're lazy or new to this, you can simply drag the folder you're working in on to terminal and the whole thing will print the path for you.

Alternatively, if you know where you're heading, you can type the first letter of each folder you're passing through and press `tab` to save your fingers all that typing.

## Installing and Task Running

Now you're in your folder, you need to install the modules you'll need. Simply type `sudo npm install` and enter your password when you're prompted.

This then installs all the cool things you'll need to get the most out of this project.

Once it's installed, you can try running the project. Type `grunt` and press enter while smiling.

Running? Amazing feeling isn't it. Now the `gruntfile.js` is where everything grunt is doing is kept. This means all `scss`, `js` and `css` files are pointed at in here. If you want to deviate from this file structure, make sure you change this file too, so it knows what you know, y'know.

## What is happening then?

When you run `grunt`, what grunt will do for you is very simple.

1. Compile all `SCSS` and `SASS` into `CSS` files for you
2. Take that `CSS` file and auto-prefix it for older browsers
3. Take that `CSS` file and combine all media queries so the file size is practically half.
4. Makes sure all `JS` is tiny
5. Runs `BrowserSync` so you can view the same site on loads of devices at the same time
6. Runs the `watch` command, which basically triggers every time you save a file, running through this list again.

So, it's doing a bunch of cool stuff for you here. Hopefully you'll have fun playing around with this.

I'm sure as you get to grips with `Grunt`, you'll want to try to expand on your tasks. I know you can do cool things like back up your files every save to another server, (Like a mac mini in the store room).

Any questions, fire me an email over to [andrew@fullphatdesign.co.uk](andrew@fullphatdesign.co.uk) and I'll try to help you out as much as possible.
