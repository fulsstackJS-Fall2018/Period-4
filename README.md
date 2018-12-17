# Period-4 
### GraphQL

*In this period we will introduce GraphQL, a new API standard that provides a more efficient, powerful and flexible alternative to REST. It was developed and open-sourced by Facebook and is now maintained by a large community of companies and individuals from all over the world.*

## [Learning Goals Period 4](https://docs.google.com/document/d/1svHB2Dp6aSfST5zaXUtpNyVy9EpO5Wpvts3_YSW934w/edit?usp=sharing)

## Snippet
[snippet-file](https://docs.google.com/document/d/1eCjER3j_-YnoOlPwyRTn8FbV9GLxsq2Uely6c20IMg4/edit?usp=sharing)

## 26-11-Monday
* An introduction to GraphQL
* Setting up a simple GraphQL backend with an Express Server and a Mongo Database

#### Before this lesson you should:

- Skim this tutorial [How to GraphQL]( https://www.howtographql.com/)
- Watch and CODE ALONG this GREAT [tutorial](https://www.lynda.com/GraphQL-tutorials/GraphQL-Essential-Training/614315-2.html) (this will give you allmost everything you need to design the miniproject GraphQL backend)
##### Hints for the Lynda-tutorial
- The tutorial uses two database (to really illustrate the power of GraphQL), but skip the part related to a relational database (SQL) --> and anything related to Aliens, and focus only the parts related to MongoDB
- The tutorial includes a section related to, how you set up a local instance of MongoDB. I suggest you just stick to your mlab-acount and create a new database up here.
-- Also skip the part (4.1) that install Robo 3T, since mlab provides you with a fine enough GUI
- It seems like the authour haven't noticed that mongoose now supports promises. So when you get to the "mongoose-part" instead of doing this:
````javascript
return new Promise((resolve, object) => {
                newFriend.save((err) => {
                    if (err) reject(err)
                    else resolve(newFriend)
                })
            }) 
````
you can just do this (but the example above, one more time, nicely illustrates how you can convert a callback based design into a promise based):

````javascript 
return newFriend.save();
````

#### Slides
[slides](https://docs.google.com/presentation/d/1Uc6r_hDfaOX0XiDidJblAd_x613hKKZU1JtbSe5DjMM/edit?usp=sharing)

#### Exercises
Complete the  [Lynda-tutorial](https://www.lynda.com/GraphQL-tutorials/GraphQL-Essential-Training/614315-2.html).
When done, start focusing on the miniproject (backend)

## 30-11-Friday

**Mini Project Backend** 
[Mini Project, part4 (Backend)](https://docs.google.com/document/d/11i1RJAfjQMgU-6RTLjcJNYyXRtAQzZOJFI-j4Kf2LVA/edit?usp=sharing)

## 03-12-Monday
GraphQL Client Side with React and Apollo. 

#### Before this lesson you should:

- Read this [introduction](https://www.apollographql.com/docs/react/) to the Apollo client, the library we are going to use for GraphQL Client Side interaction
- Read the [Getting Started](https://www.apollographql.com/docs/react/essentials/get-started.html) section of the Apollo Boost examples. This, and the sections Queries and Mutations is the starting point for the exercises for this lecture

**Slides**

[Short intro to Client-side GraphQL with React](https://docs.google.com/presentation/d/1BxWP1GbLU5yET7wTWyoBPwoX6uN-bxRla47Vg2cWTsY/edit?usp=sharing)

**Exercises:** 
- [Apollo/React-exercises](https://docs.google.com/document/d/1IIFoYyl3CMuSQ8oGHyGZBWh3-SroFyoaQWn-LPI9qVc/edit?usp=sharing)
- [Mini Project, part4 (client)](https://docs.google.com/document/d/11i1RJAfjQMgU-6RTLjcJNYyXRtAQzZOJFI-j4Kf2LVA/edit?usp=sharing)

## 10-12-Monday
GraphQL Client Side with React and Apollo continued 

**Exercises:** 
- Complete the [Apollo/React-exercises](https://docs.google.com/document/d/1IIFoYyl3CMuSQ8oGHyGZBWh3-SroFyoaQWn-LPI9qVc/edit?usp=sharing)
- Complete the [Mini Project, part4 (client)](https://docs.google.com/document/d/1IIFoYyl3CMuSQ8oGHyGZBWh3-SroFyoaQWn-LPI9qVc/edit?usp=sharing)

## 17-12-Monday
- Complete the mini project
- Any questions you might have
- About the exam

**Period Milestones:**
* Period Hand-in: December 21th. 16.00
* [Hand-in Document](https://docs.google.com/spreadsheets/d/1vnFNqFQTzYc2cu-F00xsCNkIb_Lx-NqWXtEScRFcCf0/edit?usp=sharing)

