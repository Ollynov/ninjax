# mpm

## What is NinjaX? 

There are two parts to NinjaX:

1. A library of pre-built code components that help you build apps faster. The library is open source and supported through a community, but has a pre-defined criteria for submitting new components. 

2. A command line tool that injects these pre-built components directly into your app (called boosters). This is similar to npm, but instead of delivering pre-packaged components that are ready to use (and hidden in node-modules folder), Ninjax injects the full source code directly into your app, so you can more easily customize it and understand how it is integrated.

It is possible to use NinjaX components (boosters) without the command line tool, but it is not possible to use to command line tool on a repo that is not specifically a NinjaX repo. In other words you can use #1 without #2, but not #2 without #1. However, we recommend using both, as the command line tool helps set up your NinjaX repo correctly, and integrates your boosters into your app. 

The NinjaX development process begins by downloading a "starter pack"(link), and later adding boosters(link) into your repo, which are specifically designed for that particular starter pack. As you develop, you are also free to add npm packages alongside your NinjaX boosters, as they are not the same thing, and virtually every app should have both. On a "scale of abstraction" you can imagine it like this: 

Code (javascript) --> NPM modules (bcrypt) --> Frameworks (react/express) --> Boilerplates (Create React App) --> NinjaX Starter Packs --> NinjaX Boosters --> "No Code" Frameworks (webflow/ wordpress)

Least abstracted --------- > Most abstracted


## What is a "starter pack"? 

A starter pack is a boilerplate for a full stack app. It is very similar to "Create React App" in the sense that you run one command and you have a have a small app ready to go running on your localhost. However, it is one abstraction above because each Starter Pack also comes with additional requirements such as proper state management, and and a setup for 3 dev environments. This is very much a "reverse" approach to what is typical. Normally boilerplates offer only the basics because of the 'flexibility' that it offers developers. However, one of the founding principles of NinjaX is the learning[link] that it allows developers, and we believe that having the most simple, yet correct, implementation of different verticles of a fullstack app will allow developers to more efficiently learn, therefore freeing up more time for them to create useful apps, more time for them to submit their own boosters, to write useful documentation, which in turn will open the entire dev community and allow for greater app production. As for "flexibility", it is always an option to simply remove portions which are not needed. For example, each starter comes with 3 dev environemnts set up. If you only want two of those environments, removing one should only take a couple minutes. 



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

## What is the mission of NinjaX? 

Allowing developers to both learn faster, and code more efficiently; ultimately leading to a greater growth of apps that make the world a better place. 


## What are the requirements for a Starter Pack? 

- README must be udpated with each update of code. 

## What are the requirements for a Booster? 


##### Each booster needs a starter, is specifically designed to work with one particular starter. 
In many ways it does make sense to build starters would be able to apply to various starters, but we wanted to separate concerns and ensure reliable updates to boosters as the core dependencies and starters they work for update. As a result, two boosters may be very similar- but the benefit is that if one particular one becomes out dated, it does not necessarily mean that the other one will as well.  


##### Each booster is designated either as a normal booster or a "standalone booster". 
A standalone booster requires it's own route, and is usually composed of multiple other boosters. The auth-mern booster is an example of a standalone booster. When you add it to your MERN starter, it will automatically create the '/auth/signup' route where you can view your standalone booster. This particular standalone booster is already composed of multiple other node modules and boosters. You can also add additional boosters to this standalone booster, such as the 'google-auth-mern' booster. Which brings us to the next requirement... 


##### Certain boosters require both a starter, and another booster as well. 
The 'google-auth-mern' booster requires the standalone 'auth-mern' booster to work. The downside to this requirement is that it will be impossible to ever use boosters to create a NinjaX MERN app with google authentication, but not with standard authentication (using just email and password). However, we think it will be rare that users will need this, and the upside of clarity, and perfect integration far outweigh the downsides. Furthermore, you can always customize your components as you see fit- for example you can simply comment out the ability for a user to enter in an email and password. 


##### Each booster requires a README on the same level of the code
Each booster requires a README that is clear and provides enough information to the user on how they can correctly get the booster integrated, and how they can further customize it. We also highly recommend that the code comes with comments in the actual source code of the file as well. 





