# mpm

## What is NinjaX? 

There are two parts to NinjaX:

1. A library of pre-built code components that help you build apps faster. The library is open source and supported through a community, but has a pre-defined criteria for submitting new components. 

2. A command line tool that injects code directly into your app. This is similar to npm, but instead of delivering pre-packaged components that are ready to use (and hidden in node-modules folder), Ninjax injects the full source code directly into your app, so you can more easily customize it and understand how it is integrated.

It is possible to use NinjaX components without the command line tool, but it is not possible to use to command line tool on a repo that is not specifically a NinjaX repo. In other words you can use #1 without #2, but not #2 without #1. However, we recommend using both, as the command line tool helps set up your NinjaX repo correctly, and integrates your boosters into your app. 

The NinjaX development process begins by downloading a "starter pack", and later adding boosters into your repo, which are specifically designed for that particular starter pack. As you develop, you are also free to add npm packages alongside your NinjaX boosters, as they are not the same thing, and virtually every app should have both. On a "scale of abstraction" you can imagine it like this: 

Code (javascript) --> NPM modules (bcrypt) --> Frameworks (react/express) --> NinjaX Starter Packs --> NinjaX Boosters --> "No Code" Frameworks (webflow/ wordpress)



## What is a "starter pack"? 

## What is a "booster"? 

## What is the inspiration for NinjaX and how is it different?

Better documentation: 
One of the initial points of inspiration for NinjaX is simple- the world of open source code continues to get more advanced but the documentation does not. Usually open source projects are started and maintained by the world's smartest and most passionate developers, but usually the same passion and dedication does not extend onto the documenation. 

Customizing Node Modules:
The second point of inspiration came from another frustration- when trying to customize certain node modules for projects in the past- this may involve trying to understand minimized code, understanding licensing, and individually copying and pasting portions of the source code into new project files. Node modules are meant to work in an "out of the box" way, and that's perfectly fine, but there is another important use case that NinjaX solves. 

Learning:
In the past 5 years learning has become incredibly "open source": There are free youtube videos that range from individuals teaching out of their bedrooms, to 
MIT professors delivering lectures to an audience. One vertical where this has had the most impact in has been coding- an industry that changes so rapidly that it oftentimes 'outgrows' the traditional college system of academia, and there are now more 'self taught' developers than ever before. As a result there are plenty of tutorials for new developers and bootcamp graduates on the fundamentals, but not as many good resources when it comes to the "nitty gritty" of setting up an app the correct way. The 'correct way' includes areas such as authentication, deployment, scalability, etc. Of course, one of the main skills of a seasoned programmer is to be resourceful and use Stackoverflow and the community to quickly learn. That will always stay true; however, we believe that the learning process can be sped up when the resources are presented direclty inside of your codebase, and continually updated with each new release.

The rise of the #noCode movement:



The fact that setting up a 'boilerplate' app is still an issue:


## What are the requirements for a Starter Pack? 


## What are the requirements for a Booster? 








