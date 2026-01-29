---
layout: essay
type: essay
title: "Smart Questions for Smart People"
# All dates must be YYYY-MM-DD format!
date: 2026-01-27
published: false
labels:
  - Stack Exchange
  - Reflection
  - Communication
---

*Am I stupid for asking a stupid question?*

<div class="text-center p-4">
  <img width="600px" 
       src="../img/smart.jpg" 
       class="img-thumbnail" >
</div>

## What is a smart question?

According to Eric Steven Raymond, in "How To Ask Questions the Smart Way", a smart question is one that is detailed, appropriate, and to the point. They are specific questions, with details like the operating system, the error code, the steps already taken to solve it, and the code causing the error in question. It is good practice to try everything you can to solve a problem before posting to a forum about it. 

To be appropriate, it also has to be in the right forum, and this not only includes the general idea of the forum, but also specific skill levels that the forum normally solves. If you post a question you could have solved by simply Googling a problem or reading the manual, you will most likely not get the answer you want. It is important to check if there has been any progress made on your question before, as it will save everyone time and effort.

To be to the point, the question just needs to be professional and polite. If you include too much detail like how you were up until 3 A.M downing whiskey trying to solve a problem, or you ask a question such as, "Is anyone willing to help?", people will most likely ignore your question and instead focus on your ethics. A smart question would only incldue the information needed for people to find it on the forum, pick it up, and help you find a solution.


## Some examples of smart and not-so-smart questions

[This](https://stackoverflow.com/questions/1421862/metadata-file-dll-could-not-be-found) is an example I found of a smart question, according to Raymond.

<hr>

<pre>

I am working on a WPF, C# 3.0 project, and I get this error:

Error 1 Metadata file
'WORK=- \Tools\VersionManagementSystem\BusinessLogicLayer\bin\Debug
\BusinessLogicLayer.dll' could not be found C:\-=WORK=- \Tools
\VersionManagementSystem\VersionManagementSystem\CSC VersionManagementSystem
This is how I reference my usercontrols:

xmlns:vms="clr-namespace:VersionManagementSystem"
<vms:SignOffProjectListing Margin="5"/>
It happens after every failed build. The only way I can get the solution to compile is to comment-out all my user controls and re-build the project. Then I uncomment the usercontrols and everything is fine.

I have checked build orders and dependency configurations.

As you can see, it seems to have truncated the DLL file's absolute path... I have read that there is a bug with the length. Is this a possible problem?

It's very annoying and having to comment, build, and uncomment, the build is becoming extremely tiresome.
  
</pre>

<hr>

As you can see, this question follows the basic guidelines of a smart question. It is to the point, with a good subject, and a description of the environment and problem in question. It also contains the steps the user has already taken to solve it ("I have checked build orders and dependency configurations"). The user also notes the possible source of the problem, to make things faster for anyone trying to help. This fits nicely with all the requirements of a smart question, and the replies reflect as such.


[This](https://stackoverflow.com/questions/79878152/c-sharp-equivalent-to-pythons-prophet-library) is an example I found of such a not-smart question that it went against Stack Overflow's guidelines.


<hr>

<pre>

I need to forecast some data to present in Power BI. Previously, I did this in Power BI itself via the Python script visual and the prophet library; however, it turns out that when the report is exported these are replaced with an error message if the report creator isn't a premium subscriber. Thus, I am instead going to forecast the data outside Power BI and then import the forecast.

The raw data is stored in an Azure SQL Server database, so I would like to be able to access it using my existing EF Core setup—hence why I want to switch to performing the forecast with C#.

If it helps, the data is a time series of monthly donations for a nonprofit. It exhibits trend, minor seasonality, and extremely large holiday effects.
  
</pre>

<hr>

This question fails to follow some of the guidelines for a smart question. Instead of a programming problem to solve, the user is looking for recommendations on products to use, which is not appropriate for the forum they were posting in. Also, it is unclear exactly what the user wants as an answer. There isn't a single question mark or request directed at readers. As a commenter says, this question would be better posted in an off topic channel, where there is more leeway on product recommendations and the like.

## Should I still ask a not-so-smart question?

If you are thinking whether or not it is appropriate to ask a question in a certain forum, then there is more than likely another avenue to post your thoughts and questions. It doesn't have to be on Stack Exchange, where there is an expectation of how a question should be asked and at a certain skill level. Instead, it could be on a place like a public Discord server or a physical classroom with students. More casual questions like that are actually encouraged in more lax environments, as people usually don't want to start spending the rest of their break time solving your problem, and most usually like to get into some small conversation. In general, if you are going to ask a question in an online public forum, just double check that it is appropriate before people have to publicly tell you that it isn't.
