---
layout: post
title:  "Pick Your own Topic!"
date: 2016-02-18 08:10:05
categories: jekyll update
keywords: "If vs case"
categories:
- Programming
tags:
- Programming
- Language
---
--- Both the case and if/else statements are key components of even the most basic of programs in the Ruby language. They serve very similar purposes, but each of their own unique aspects of them that cause their use within programming to differ. Each of these statements compares multiple outcomes against one another. They both serve the general purpose of when “x” happens, do “y”, but if “a” happens, do “b. A main factor in the use of one over the other is the simplicity. Case statements often times are quicker in that they literally say something along the lines of:

switch(myObject.GetType()){

    case typeof(Car):
        //do something
        break;

    case typeof(Bike):
        //do something
        break;

    case typeof(Unicycle):
        //do something
        break;

This example looks very straightforward, but at the same time is rather complex to understand and is not overly semantic. However, the use of the case statement is often faster to craft as well as more efficient to the writer, but decreases efficiency with other people, specifically readers. Also, case statements being smaller in size often than if statements allows for programs to be processed faster. This difference in speed is negligible in small programs, but larger programs and their writers do notice this subtle difference. In comparison, an if/else is constructed like this:

 if (myType == typeof(Car)){
            //do something
   }

   else if (myType == typeof(Bike)){
            //do something
   }

   else if (myType == typeof(Unicycle)){
            //do something
   }
   else{

   }
While this is written in a demo format, with the variables filled in this format is much easier to understand from the standpoint of the reader but is often more tedious to write and construct. As mentioned above, if/else statements make up for their lesser speed with simplicity and solid semantic characteristics. Overall, both if/else and case statements hold their own advantages and disadvantages, but both play more than important roles in the composition of programs.





CS First Blog Post Sources:
http://www.daniellesucher.com/2013/07/ruby-case-versus-if/
http://stackoverflow.com/questions/2158759/case-vs-if-else-if-which-is-more-efficient http://stackoverflow.com/questions/767821/is-else-if-faster-than-switch-case
