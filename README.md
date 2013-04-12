Node-Eclipse-Studio
===================

[Node on Eclipse Studio (NES)](https://github.com/Nodeclipse/Node-Eclipse-Studio)

**HELP NEEDED !!!**

<!-- DONE wit NODE  -->

## Goal

The goal of the project is to created the lightest Eclipse Distribution for Node.js development.

Of course it will include [Nodeclipse-1 plugin](https://github.com/Nodeclipse/nodeclipse-1).
 See [Nodeclipse team blog](https://github.com/Nodeclipse/nodeclipse-blog#blog)

It should not include Java Tools, but EGit, possibly JS & Web tools.


## Status 

*Under investigation, probations*

 
### Second attempt - Googling
 
[Create your own Eclipse distro made easy](http://tomsondev.bestsolution.at/2012/07/13/create-your-own-eclipse-distro-made-easy/) 
 July 13, 2012 by Tom Schindl
 
https://github.com/tomsontom/distrobuilder cloned to https://github.com/Nodeclipse/distrobuilder

3) http://www.genuitec.com/sdc unaccessible

Using preinstalled Jenkins Virtual Appliance 
http://bitnami.com/stack/jenkins

## Options

### Yoxos

Warning: before taking steps, read conclusion first.

I am trying to create our own Eclipse distribution using yoxos.

The start is simple ( just navigate to https://yoxos.eclipsesource.com/discover.html
and click "create your own custom install" )

However I have not succeeded with what to do next. The site is a bit mess. It is not clear if it is fully free.

UPDATE:

I created profile NES4.2 (based on Eclipse 4.2 + Git + JSDT + Nodeclipse).

![Yoxos-JS-Git.PNG](Pictures/Yoxos-JS-Git.PNG)

This is link to plublic profile to download, but you need to register on yoxos
https://yoxos.eclipsesource.com/userdata/profile/fe0ceddd57f38b2e461c1e96a508d1c1
Now anybody can download this profile.

Download is zip file for specified platform (just like Eclipse).

First start takes 30sec longer.

Then it intrusively requires login to with yoxos account (If you press X to close window, it pop-ups again 1-2 times.) :-(

![yoxos-intrusive.PNG](Pictures/yoxos-intrusive.PNG)

After restart (I needed to add ChromeDevtools, as there were not referenced in profile),
Yoxos requires login again, and becomes unresponsive when "fetching distribution... " What the hell!

![yoxos-fetching-distribution-info.PNG](Pictures/yoxos-fetching-distribution-info.PNG)

#### Yoxos conclusion

Big disappointment. https://yoxos.eclipsesource.com web pages advertise that it is so simple, then you spend several days
 on learning how to in absolutely NOT straight-forward way, and when you get result it is not accomplished, slow, intrusive.
It is not Eclipse distribution, but one more Yoxos launher apllication.
The advertising pages are misleading.  

### Genuitec

http://marketplace.eclipse.org/content/secure-marketplace

It seems to need license.

## Contacts

If you only need to install set of plugins, check [Eclipse Node IDE](https://github.com/Nodeclipse/eclipse-node-ide).

* How do I? -- StackOverflow!
* I got this error, why? -- StackOverflow!
* I got this error and I'm sure it's a bug -- file an issue!
* I have an idea/request -- file an issue!
* Why do you? -- the mailing list!
* When will you? -- the mailing list! 

Node on Eclipse Studio (NES) by [Paul Verest](mailto:paul.verest@live.com?subject=NES - Question
&body=I have pressed link in README.md)

If you want to contribute and actively work together, then [email](mailto:paul.verest@live.com?subject=NES - Development
&body=I want to contribute to Node on Eclipse Studio (NES))  
Skype pverest  
QQ 908781544  

## For Bloggers and Users of Twitter, Flickr, LinkedIn, Weibo etc.

In case you plan to blog or tweet about the Eclipse Node.js IDE, please use the tag "#Node-Eclipse-Studio"
 in order to make it easier to find all the comments and pictures. Thanks a lot for telling the world about the project!  
  | 请用#nodeclipse# #Node-Eclipse-Studio#标签微博一下。  
  | Por favor, utilizar etiqueta #nodeclipse #Node-Eclipse-Studio  
  | ツイートする時は、#nodeclipse ＃Node-Eclipse-Studio タグを使用してください。   
  | Bitte benutzen Sie tag #nodeclipse #Node-Eclipse-Studio um zu twiten.
 
