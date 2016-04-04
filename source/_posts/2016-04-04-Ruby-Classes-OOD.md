---
layout: post
title: Ruby Classes and OOD
date: 2016-04-04 09:21:30
comments: true
description: "An informative post on the advantages of classes and OOD"
keywords: "Class", "OOD"
categories:
- Ruby
tags:
- Ruby, Class, OOD,
---
Object oriented programming uses an object which you use as a vehicle or an agent essentially. An object, which is found within code at the head of a Ruby class, both contains data and controls access to it. Classes contain these objects at the head who within the class have defined features and actions called instance variables and methods respectively. Classes are utilized in order to both store and control access to data. All major web applications use classes in some capacity as the main advantages of classes pertain to its efficiency and simplicity. Object Oriented code becomes the optimal choice in web app construction as it posses attractive benefits over single block code, while also providing an effective way to store data in the form of methods and variables. OOD is an effective way to store data within classes in the creation of a web app or other code project. Methods and variables can extract data from the object as well as allow it to perform actions and/or functions. There are some disadvantages of using classes and object oriented design, especially pertaining to the construction. Often times going through the creation of a class can be tedious and can in some cases take significant amounts of time to form and define each method and variable. An example of the tool I have been describing is as follows:


class Car 
	
		def initialize (color, model, make)
			@color = color
			@make = make
			@model = model
			
		end
		
		def no_of_horsepower=(no_of_horsepower)
			@no_of_horsepower = no_of_horsepower
			end 

			def no_of_horsepower
				return @no_of_horsepower
			end 

		def trim=(trim)
			@trim = trim
		end

		def trim
			return @trim

		def engine
			@engine = engine
		end
end

This class posses a name, being the first part, and then has both methods and variables to follow it.  A method is a part of the class which instructs the objects to do something, being an action or more specifically a retrieval of data. An example of this within the class is any of the aspects with “return” which would display the data stored within the variable that follows it. On the other side, the variables are the attributes of the car, be it “no_of_horsepower” or “trim” act as the instance variables or data within the object and thus the class. Overall, classes and the data within them provide an effective and efficient method for web application creators to store and access data within their code. 













Sources:
http://www.tutorialspoint.com/ruby/ruby_classes.htm
http://ruby-doc.org/core-2.2.0/Class.html
http://rubylearning.com/satishtalim/writing_our_own_class_in_ruby.html