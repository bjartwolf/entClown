# Outline
# Intro
## Living with a split personality
Hi. I am @TheEnterpriseClown and @bjartnes. @bjartnes is a SharePoint Developer at Computas. @TheEnterpriseClown is the alter ego of @bjartnes. When @bjartnes would install Visual Studio 2012 and TFS, his alter ego is fed with rage, screaming for VIM and git. When @bjartnes carries his huge 32 GB RAM 2 spinning disks SharePoint dev environment around to the next scrum demo, almost breaking his back, you'll find @TheEnterpriseClown wants to go to a cool cafe at Tøyen to hack on his ultrabook.

I'm not making fun of personality disorders here. I'm just struggling myself between trying way to hard to be a cool hacker with a linux ultrabook and the fact that I make my money building SharePoint applications for the Enterprise. Being laughed at in all camps.

At some point I tried to bridge the two by building SharePoint apps with node.js. This is the story of when my two personalities hooked up.
## Real-time apps
I needed an excuse. I'll come back to why, but real-time apps for SharePoint seemed hip, something SharePoint tradionally don't do a lot of 

## Example
I'll start with the end, what did we build (with some collegues @jornare, @askildt and @Ellafy) at the Arctic SharePoint Challenge 2013.
https://github.com/bjartwolf/entClown/blob/master/demo.mp4?raw=true
https://github.com/bjartwolf/entClown/blob/master/multipleDevices.mp4?raw=true

# Architecture
## Node
Not just "javascript on the server"
Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

## SharePoint 
You know this guy, right? Still monolithic and massive, but with a new REST interface, who cares how he works on the inside?

## Node and SharePoint 

![architecture](https://raw.github.com/bjartwolf/entClown/master/architecture.jpg)

![auth](https://a248.e.akamai.net/camo.github.com/040c84c785b08fc19dd31c7c3f54273614621da7/687474703a2f2f7777772e676c696666792e636f6d2f707562646f632f343331383035362f4c2e706e67)

# List of modules 
- express
- passport
- passport-oauth
- oauth
- jwt-simple
- socket.io
- jade
- request
- connect-ensure-login


# Points I want to make
- understand the decoupling
- async, web, servers in multiple locations
  Node is 

# Thanks too
I took some code from QuePort  

https://github.com/QuePort/passport-sharepoint

https://github.com/bjartwolf/SP2013Node 

Thanks to @askildt, @jornare and @ellafy - we all built this at the Arctic SharePoint Challenge 2013.
