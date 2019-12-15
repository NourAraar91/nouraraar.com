---
title: "How Developer Should Design"
date: 2019-12-14T18:23:39+08:00
draft: false
author : "Nour Araar"
categories : [""]
description : "How to Think Like A Designer"
featured : "cover.jpg"
featuredalt : "How Developer Should Design"
featuredpath : "img/developer_design"
linktitle : ""
type : "post"
---
For a long time, the design represented a difficult challenge for the developer, and because the developer always tries to think in a way that they fill in logic, the design sometimes contradicts this aspect and needs more on the creative side But before we continue on how to find a solution to this issue, let us know why design is important

# Why Design important ?
The design is of great importance for several reasons 
1. Users see and care about the design,they don’t see the complex code:  
   First thing the user will judge when he opens your app is the design ,
   the better the design the more likly the user will love your app so it's mor important than the code
2. The user experience is crafted by design:  
    it's clear that every idea and new feature in the company has to run by the designer 
    who will do research and build the design in a way that will make the user experience better

after we know the importance of the design let's go through the current process of designing and try to improve it :)

# How Developer Do Things currently ?
first he will get the design files from the designer ,"who uses tools like sketch and zeplin"  
and start to mock them up using his development tools like (xcode , android studio or any text editor for the web developers)   

**Example of an app screen:**  
![Example of an app screen](/img/developer_design/sign_up_page.png "Example of an app screen")  
as we can see an Example for a signup page here the develoepr will start building the componanets of the page  

**Simple Component Example:**  
![Simple Component Example](/img/developer_design/element_example.jpg "Simple Component Example")  
each component has mutible attributes like    
1. Font
2. Text Color
3. Border Color
4. Background Color
5. Placeholder Color and Font
6. Multiple States (enabled, disabled, selected)  

now the developer will start reading these attributes for each componanets from design application to code

# Why is this not recommended?
1. Design takes 2/3 of the time when building any project
2. High chance of having human errors
3. Not easy to build complex design
4. High effort required to change and maintain the design  
   
## How much time does it take? To build a simple design?
![do Math](/img/developer_design/do_math.gif "Do Math")  
![do Math](/img/developer_design/math.gif "Do Math")  
![Number of operations](/img/developer_design/number_of_process.png "Number of operations")  
```
this number is releated to the developer and will change from one to one depending  
on the developer speed of building the things
```
but as an avarage and just for comparing purpose  
that mean for avarage it will take about **32 days** to build the design

## How can we reduce time needed? And build better and more complex designs?
*since this is a designers process so it is better to do it their way, what does that mean?*  
designers build things using symbols that can be reused evrey where ,  
that mean they build the symbole once and have it where ever they want 
and when they need to use it again they just call the symbole name and if they wanted to do some changes they just update the symboles file
and it will be reflected every where.

## Introducing Atomic Design Methodology
```
Atomic design is a methodology composed of five distinct stages working together 
to create interface design systems in a more deliberate and hierarchical manner. 
```
The five stages of atomic design are:  
![Atomic design is atoms, molecules, organisms, templates, and pages concurrently working together to create effective interface design systems.](/img/developer_design/atomic-design-abstract-concrete.png "Atomic design is atoms, molecules, organisms, templates, and pages concurrently working together to create effective interface design systems.")  

Atomic design is not a linear process, but rather a mental model to help us think of our user interfaces as both a cohesive whole and a collection of parts at the same time. Each of the five stages plays a key role in the hierarchy of our interface design systems. Let’s dive into each stage in a bit more detail.


## How do we put it into practice?
as we can see it just a way of thinking and organizing your elements and style,  
so instead of start building the design from top-down (building the pages then the elements),  
we go the opposite way down-top,that mean we start from the atoms
```
Atoms are the simplest element such as labels, buttons, inputs and images
```
![Current Way To build things](/img/developer_design/top-down.png "Current Way To build things")  
this is the Current Way To build things so in order to build the design we have to go through every element and component in the design that will result as we already found around **~ 15000** operation to build  
so instead of building that number of componenets we only build the unique compomenets and use them around the app and as a result  
### How much time do we use now? Currently we have about 20 unique components
![do Math](/img/developer_design/do_math.gif "Do Math")
![Number of operation after we applied the Atomic design methodology](/img/developer_design/new-results.png "Number of operation after we applied the Atomic design methodology")
since we don't care any more about the number of screens and number of components in it we only care about the number of unique components in our design the number of operation goes down to **~900** instead of **~15000** and that is a huge improvment in the designing process

## what we achieved now ?
1. our design now is more orgnized and readable
2. number of operation reduced to 1/10 of the old way
3. now can build more complex design from what we already got
4. now can foucus more on the logic not the design
5. the time to maintain and change the design goes from days to hours  
   sice you have now only to change the unique componts only from one place

now as a result for that we are now agreed that
```
let the design process for desingers
```
and foucs on your code and logic of the app
