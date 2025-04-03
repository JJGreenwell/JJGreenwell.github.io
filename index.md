---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

# Introduction

I am a CS student at SNHU who develops programs with the intent collaboratively work to create programs that can provide intuitive solutions to commom issues faced by the end user. This portfolio contains a number of example programs and explanations of my experience and abilities within the development field.

# Professional Self-Assessment

For over four years now, I have been studying and polishing my abilities within the field of computer science. While I have my own strengths and weaknesses in this area, I feel that you will find that throughout my time and efforts I have developed skills that are useful and relevant to the industry. Throughout the past few years, I have been studying computer science at university, which has given me the opportunity to hone and polish a number of relevant skills. While I have struggled with certain issues in the past, the efforts dedicated to my studies have increased my necessary capabilities dramatically.

One such example can be seen within the projects displayed within this portfolio. Looking at the original code for my mobile event tracking app, you can see it was initially developed with a very individual mindset; code structure and commenting had little to no detail in certain areas. Throughout development, documentation was barely present. In my mind, since I was only developing code by myself that would only be adjusted by myself, it seemed unnecessary to pay extra efforts to make it easy to follow and adjust for others. However, throughout my continued efforts, I began to shift my mindset to be more team-oriented and began to understand the need for code to be written with a group environment in mind. I began making efforts to adjust readability and communication within my programs, and began putting in extra work to document better for others. 

As a side effect of this development, I feel that a collaborative mindset has become one of my greatest strengths. However, I do feel that I have developed many other useful competencies as well. My efforts put towards increased communcation could prove beneficial in situations where an individual group may need to communicate with shareholders or clients. As for more code and development related abilites, I have consistently developed programs that require the use of data that needs to be efficently handled and adjusted by a number of different elements. This typically requires me to use a number of SQL and data handling tools such as MongoDB, pandas, Numpy, Express, and more, which I believe has granted me a healthy level of competence with areas of expertise such as data structure, algorithms, databases, and data handling. Furthermore, my programs typically require a number of both front and backend elements, meaning I have gained a strong level of experience not only with writing code, but also with adopting strong, user-oriented UI and UX design elements, while also adopting certain full stack programming practices through the use of practices such as the MEAN stack, which I feel has given me crucial experience towards developing clean software engineering practices. Of course, user focused programs always need to consider the safety and integrity of the user's and their data, which has pushed me to grow my level of competence with healthy security practices. A number of my projects regularly include the use of features such as proper certifications, encryption, and secure practices to combat common vulnerabilities such as buffer overflow and injection attacks.

While I still have room to grow, I have spent the past years working meticulously to increase my abilites, which I feel has caused me to gain a significant level of competence that can be useful on any team, while still retaining a desire to hone in my efforts and grow my abilites even further.


## Informal Code Review

To help you understand my processes and constructive review process, I have included and informal code review here to help you understand how I like to approach my projects and continously seek to improve them while considering the needs and convenience of the intended user.

[You can find the review here](https://youtu.be/NVShMZ97_Kc).

# Enhancement One - Software Design and Engineering

The first enhancement within the Computer Science Capstone focused on improving the quality and design of a previous project in a way that makes its use easier for the user and more intuitive for the developer. To demonstrate growth in this area, I chose to make improvements to a mobile event tracking app I developed as the final project of a previous course of mine, focusing on making user-oriented updates and bug fixes to the application.

[Original Project Files for Artifact One](https://drive.google.com/file/d/11lUc3otRJp-CgZNWWf0cklkguzhpr94h/view?usp=drive_link).

[Enhanced Project Files for Artifact One](https://drive.google.com/file/d/1MjyyUWfHNJwKKFp8dmLEqbIjcVN3rYE0/view?usp=drive_link).

### Enhancement One Narrative

To demonstrate an understanding of strong software engineering practices and how to incorporate them in a professional manner, I opted to enhance a mobile application that I developed in CS 360, a course I took previously in college. The application is an event tracking app, which allows users to add and edit events, view various details about them, and receive reminders about them when they are close.

I felt that this artifact was a good choice for this enhancement due to the many features that it includes and how they interact with each other. It makes use of multiple screens and functions that each handle pieces of different data in various manners, while still connecting these functions with each other in a way that is effective for meeting the user’s purposes. Demonstrating an ability to develop features that meet these needs in an efficient manner can express an ability to understand and consider user requirements in a professional manner, making this a good choice for an enhancement.

The actual differences between the original and enhanced products contain several quality-of-life adjustments and bug fixes for the user, mixed with some improvements to code functionality and layout. While this adjustment is one that wouldn’t be noticeable to the user, I went through and completely renamed most of the elements and files within the program to make the entire program more readable and easier to work in. As far as enhancements that do effect the user, I was able to improve the amount of information on the home screen by also displaying the date to the user along with the event name. This one small adjustment could still prove to be useful to the user, especially when combined with the added functionality of sort features. I was able to add a dropdown that currently gives the user a way to sort their events either alphabetically or by date, which can allow the user to more easily access the right events for the right situations. Additionally, the original method for sending notifications about an upcoming event relied on hardcoded variables that were only relevant to the time that I was developing the program in. I added a new way of determining the date range, which is adjusted dynamically for any given day.

Some of the bugs that were fixed are as follows: when updating an event, but not updating the name field, this would cause the event to be deleted. This was done to prevent accidental duplicates from being created, and while that did work, it lost functionality if the name field were ignored. A simple if-else check was able to save this. There was also an error that occurred on the login and create account screens when adjusting text. The text listener would not always null out the sign in button if a field is blank, and while there was a check later that kept this from being an issue, it still felt wise to fix it. By updating the logic on the field in the text listener, I was able to get this functionality to operate properly, which also allowed me to clean up later code, as I was able to remove the if branch that checked for null inputs.

Reflecting on the first module, I anticipated that my enhancements in this field could meet the second, third, and fifth outcomes for the course.  Now, my plan for meeting the fifth outcome is largely influenced by the suggested addition of methods to prevent buffer overflow. However, when I initially considered that idea I failed to consider Java’s use of char arrays, meaning that overflow would not occur in the instances I anticipated it could. So while I feel that security methods were not a strong focus of this enhancement, I do know that they will be present in future ones. For the other outcomes, however, I do feel that the proposed outcomes were met. The adjustments to allow more information to be displayed to the user at once delivers professional visual communication to the user, thus achieving the second outcome, while the use of sorting data based on selected filters can relate to the algorithmic means of solving user problems mentioned in the third outcome.  While I did not discuss this outcome in the first module, I do feel that the enhancements also cover the fourth outcome, due to the use of the many different tools and features to implement user-centric solutions to several potential problems.

Enhancing an artifact with the level of freedom I had in this instance seemed a little different compared to some past instances, as I am typically used to following a much stricter set of requirements in a particular order. While this level of freedom was nice, it did cause me to face an issue earlier on, which was determining how to focus on specific adjustments at a time. I would constantly find myself jumping back and forth between working on different features at once, leaving the full enhancements unfinished as I would start work on the next one. This could be an issue, especially as it can prevent me from isolating certain issues that could arise from a given enhancement. Facing this challenge really helped me learn how to pace myself and choose to update and develop features for the sake of the program, which I know is something that will prove to be useful to both me and others in my future projects.

# Enhancement TWo - Data Structure and Algorithms

The second enhancement focused on improving the use of data and how it is structured and handled within a program. To demonstrate enhancements in this area, I updated my project that was originally the final for a client/server development course, improving the sort methods and data handling logic in various areas throughout the program.

[CS 499 Artifact 2 Original - Greenwell.zip](https://github.com/user-attachments/files/19579621/CS.499.Artifact.2.Original.-.Greenwell.zip)

[CS 499 Artifact 2 Enhanced - Greenwell.zip](https://github.com/user-attachments/files/19579615/CS.499.Artifact.2.Enhanced.-.Greenwell.zip)

### Enhancement Two Narrative

For the second artifact and enhancement, I opted to select the final project from CS 340, which is a dashboard for displaying various pieces of information related to shelter animals within a company’s database. This specific project involves the use of a database which already contains a lot of information which is handled in several ways, so I felt it was an ideal choice for this specific artifact.

There are a few features within the project that display an understanding of algorithms and data structure, the most notable ones being the filter options, sort options, and the methods of storage present within the dataframe. I made improvements to all these areas from the original artifact, and I feel that they now demonstrate an increased understanding of my data structure capabilities.

One of the first and most simple yet effective improvements was changing the data type used for each field. By default, Pandas stores items in a dataframe as a type “object”. This would lead to every column within the frame taking up around 80000 bits. However, by manually converting certain items to float32 and making use of pandas “categories,” I was able to cut this down by more than half, making the program smaller and more efficient to handle. From there, I also added a means to sort the display of the items within the dashboard by either name or ID. To do this, I used pandas to implement a quicksort method to sort through all the data as necessary. Quicksort is effective at sifting through large amounts of data at once in a quick and efficient manner, with its average complexity being O(n log n), making it a better choice than many other options. Now, the worst case in quicksort is O(n^2), which occurs when sorting through data that is already mostly in order. However, by locking the sort methods to radio items, this ensures that the method is never being applied to a dataframe that is already mostly sorted, keeping the sorting time complexity around a healthy O(n log n). These sorting methods are also applied in a way that allows it to cooperate with the already existing filter types, meaning that changing the filter and sort methods at any time won’t cancel each other out or cause issues. These changes in turn made the program much more convenient for the end user as it gives them more control, but also more efficient as data is handled more smoothly and intuitively.

Looking back, I felt this enhancement would meet the first, third, and fourth outcomes. After finishing the enhancement process on this artifact, I would say that I feel that was an accurate prediction. I made use of user-friendly documentation and reporting while editing the code, I implemented algorithmic principles with intuitively weighed trade-offs while making use of several different techniques, skills, and tools, all of which deliver a more quality product to the user. While I don’t feel I have met any more outcomes than I initially predicted, I am happy with the progress I have made towards the ones listed.

This project made use of data that is being passed through several places: from a file to a MongoDB database, then to a dataframe, and from there to a datatable. I found that one thing that gave me the most difficulty when finishing this project was figuring where I should manage the data in a given context: sometimes it was better to adjust and manage it directly from the database, other times it was better to adjust the dataframe, and so forth. I found that there were times I would make the wrong decision in these cases and would try to handle the data in one area when it would be better handled in another. However, I feel that this eventually led me to have a better understanding of how to manage data that is used in different areas. Additionally, the use of so many tools and methods within one simple program really helped me learn how to use these tools in more effective and ideal manners, which I’m sure will prove useful in future ventures. 


## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
