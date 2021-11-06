# Object-Oriented Programming in JavaScript

You are not the only one to feel that JavaScript is weird. This is very common for people coming from other backgrounds. That's because JavaScript is not like those traditional class based languages.

## 1. History

It is important to know the historical context around JavaScript's creation. In 1994 Netscape relased their web browser called Netscape navigator. The web browser was a major success. Brendan Eich convinced his boss at Netscape that the Navigator browser should have its own scripting language. At that time Java was very very popular. Netscape was negotiating with Sun to include it in Navigator. The big debate inside Netscape therefore became “why two languages? why not just Java?”. 

They eventually decided to come up with a new language for their browser. But the diktat from upper engineering management was that the language must look like Java beceause they wanted to attract Java programmers. At the same time, they didn't want to compete with Java. So Brendan Eich did something different for JavaScript. He chose first-class functions from [Scheme](https://en.wikipedia.org/wiki/Scheme_(programming_language)) and prototypes from [Self](https://en.wikipedia.org/wiki/Self_(programming_language)) as the main ingredients.

## 2. What is an Object?
In order to understand OOP in JavaScript, it’s important to understand the concept of objects. They are a primary part of JavaScript. Almost everything in JavaScript is an object.

> An object in JavaScript is simply a key-value pair where key is a string and the value can be anything.

It's simillar to a data structure called hash table. However, the implementation can vary on different JavaScript engines. 

### 2.1 Readings
[Performance of key lookup in JavaScript](https://stackoverflow.com/questions/7700987/performance-of-key-lookup-in-javascript-object)