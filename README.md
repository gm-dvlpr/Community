# Community
This repository is used for gm-dvlpr's 'java.awt-Game'. 
We are going to code a 2d platformer game for Java 8, using the awt-library.

gm-dvlpr is a german developer, making tutorials about programming, especially for Spigot and
BungeeeCord on his channel.
This repository is used to manage the code which is produced by gm-dvlpr and the community.
The project was started on beginning of July 2015 and has the goal to code a BedWars-Like Spigot-
PvP-Plugin and is still not finished yet! - This means that you can help us (see below).


####__How does it work?__
Maybe you don't believe that something like this project works. __But it's simple:__
1. Every public tutorial causes new code which will be pushed to this repo
2. If someone has an idea to improve or extend this plugin, it's possible to do that and create a pull
   request
3. Pull requests will be reviews by one of the collaborators
4. If everything is well, the changes will be merged with this public code-base
Larger choises aren't desided by only one - we'll create a public available poll where everybody can
vote. After voting we are going to analyse the result.


####__Get involved__
Would you like to participate in these project?
There are a few different ways to contribute:
* Extend or improve the sourcecode (more detailed information below)
* Translate our language files
* Report bugs and errors
Questions? No problem ... just ask us.


####__For Developers__
Fell free to join us! Clone the repository, modify the sourcecode and start a pull request!
We need __every__ developer! Even if you are a noob, beginner, advanced learner or expert! We have
enough things to do!
If you are not familiar with Git or GitHub you can look for tutorials in the internet. A lot of information
can be found [here] (http://git-scm.com/docs/gittutorial).


####__Coding Guidelines__
Please keep in mind that we observer the [Google Code-Style Guidelines] (http://google.github.io/styleguide/javaguide.html). Additionally we are working with Java SE 8 / JDK 1.8. Therefore you'll need a Java compiler for language level 8 or higher to
compile the source. However, there are some important exceptions / changes:
* License notes are not required - all code is licensed under project license (__MIT license__)
* @author tags are __not allowed__ - enough attention to the authors is given in __plugin.yml__
* Tabs are allowed for identions; but only __1 Tab__ instead of __4 Spaces__
* It's allowed, but not required to declare interface methods with additional __public abstract__
* It's recommended to work __without__ whitespaces in statements¹

> ¹ Style for statements, parameter-lists, ...  
> Recommended: if(true) { ... }  
> Not recommended, but allowed: if( true ) { ... } 


#####__For Server-Owners__
This project is published under the terms of the MIT-License, which can be found in the project
(LICENSE.md) or [here] (http://opensource.org/licenses/MIT).
That means, you are not allowed to do _anything_ with the code as long as you _don't_ remove the notice!
But note: You have to compile the project _yourself_ to get the plugin JAR-File!
To compile the sourcecode, clone this repository or download all files (download ZIP) and let your Java
compiler (e.g. javac) run. To run the compiled plugin you need a JRE (Java Runtime Environment)
version 8 or greater.
