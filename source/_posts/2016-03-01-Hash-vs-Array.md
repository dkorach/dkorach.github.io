---
layout: post
title: When to use a Hash vs an Array
date: 2016-03-01 09:11:13
comments: true
description: "An informative post on hashes vs arrays in Ruby"
keywords: "Hash", "Array"
categories:
- Ruby
tags:
- Ruby, Hash, Array
---
There are multiple differences between the function and use between a hash and in array in Ruby programming. To start, an array is a list of numerated objects that can range from names to hashes with each labeled with a number starting with 0 and ending with the quantity of objects minus 1.A specific object array can then be referenced by its name at any point in the code which allows people to navigate through their program with increased ease and simplicity. An example of an array is written like this:

array = ["John", "Robert", :name, 557]

The objects from this array, as previously mentioned, can be referenced at any point by calling their number. This would look like: “puts array[1]”. This command would retrieve the object named “Robert” as the first object is “array[0]” which can be a confusing aspect of arrays, but the ability to call these objects at any point during the program is the main advantage of using arrays. 

Hashes however, are made up of objects called key-value pairs which are organized by the order in which they were added. Hashes consist of key-value pairs rather than simply objects which are a collection of a key, which is a unique identifier for the KVP, and a value which is the data itself. The values are enumerated based upon the order that each KVP was integrated within the hash. An entire hash looks like this: 

hash = {"friend1" => "John", "friend2" => "Robert", :attribute => :name, :number_of_hours => 557, 1996 => "Best year!"}
	
While hashes and arrays have similarities between them, they both share the common advantage of improving overall simplicity and semantics throughout a program. The main difference however is the fact that a hash gives a key to each value, rather than an array which simply provides a value. The key then can be referenced by its name rather than numerically and can then be used specifically rather than calling an object from an array. The hash provides a more detailed value than an array, but at the same time a hash can be an object within an array so even though they have differences, they both have similar functions and can even be intertwined. 


Sources:
http://stackoverflow.com/questions/6097637/whats-the-difference-between-arrays-and-hashes
https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63 
https://teamtreehouse.com/community/when-do-you-use-an-array-versus-a-hash-in-ruby 
