
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 16 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Working with JSON and XML

A substantial part of the job of a professional data scientist is to find and access data. We've spent a bunch of time looking at how to pull information from relational databases, but there is lots of information you might need to work with that is either not in a relational database, or that is not exposed to you via a relational database. 

For example, you might work with a third party website that has a lot of geographical data (perhaps points of interest near state highways). Within their company they may well store the data within a relational database, but you might have to access it using an API (an Application Programmming Interface - a way your computer can talk to their computer to go get some information!). Over the next couple of sections we'll be looking at acesssing data through APIs and enough HTML and CSS to get started with web scraping (downloading information automatically from websites). In this section, we're going to look at a couple of key data storage formats that you may well come across when retrieving data from other web applications or from inside your company.

### JSON and XML

We start off this section by providing a brief introduction to both JSON and XML so you know what they look like and their relative strengths and weanesses. We then get some hands on practice loading and parsing data from both JSON and XML formatted files into Python.

### JSON Schemas

Now that we've learned how to import data that has been stored in the JSON format, we look at JSON schemas - a way to describe the expected structure of a given JSON file.

### Recursive Functions

Next we take a bit of a side step to introduce recursive functions. A recursive function is one that calls itself - perhaps many times. Recursive functions can be used to write incredibly terse and powerful solutions to certain types of problems. They take quite a while to get used to, but once you learn how to use them you'll be surprised at how often they can help you to solve a problem that would otherwise be much more difficult (or even impossible) to solve. We're introducing them now, because recursive functions can be a very powerful tool for parsing JSON or XML documents that could have very deeply embedded information (e.g. a person has worked at many companies, each company has many addresses and each address has many staff each of which has an email address).

### Exploring JSON Schemas

From here, we'll get a lot more practice working with JSON schemas, exploring unknown schemas, accessing and manipulating data inside a JSON file and then converting JSON to alternate data formats. This lab will be a great chance for you to practice your Python programming skills, work with recursive functions and get comfortable with importing and transforming JSON data - something you may well have to do on a regular basis as a professional data scientist.

### NoSQL Data Stores

We finish off the section with a litle aside to introduce the idea of databases that are not relational and don't use SQL for data access - often called NoSQL data stores or databases. It's just a brief introduction to a huge topic, but increasingly in companies you'll find more and more data saved in NoSQL data stores, so it's important to at least know what they are.


## Summary

Whether its from an API or a NoSQL store, it's quite possible that some of the data you find yourself working with will be stored using eithert XML or JSON. In this section, you'll build the confidence to be able to import and transform such data.


