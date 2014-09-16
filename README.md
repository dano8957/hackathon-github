# Team Members

* [Niklas Fejes](https://github.com/nfejes)
* [Alex Tsankov](https://github.com/antsankov)
* [Daniel Nolan](https://github.com/dano8957)
* [Marc Simpson](https://github.com/masi8397)
* [name-of-a-team-member](URL to this member's github account)

# Objective 1. Node.js

[grabevents.js](grabevents.js)

# Objective 2. Reanalyze

### 2.a. What is the distribution of push requests over Github accounts?
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](http://imgur.com/q1EUyAI.png) 

### 2.b. How are different event types compared over time for the whole class?
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](http://imgur.com/FVn1OKJ.png) 

### 2.c. Who had the most number of pull request events?
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](http://imgur.com/o4xgqIT.png) 

### 2.d. How many different kinds of pull request actions were made?
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](image.png?raw=true) 

### 2.e. What is the distribution of opened pull requests over Github accounts?
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](image.png?raw=true) 

### 2.f. What is the submission pattern (i.e., pull requests) of the "Week 2 challenge" over time?
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](image.png?raw=true) 


# Objective 3. Analzye Week 3

### Question 1. {{write-the-question}}
```
sourcetype="events3" type="PushEvent" | timechart count by actor.login
```
![screenshot of a data table or a graph or both](http://imgur.com/OyIrxZn.png) 

{{ write-one-or-two-sentences-to-discuss-the-answer}}

### Question 2. {{write-the-question}}
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](image.png?raw=true) 

{{ write-one-or-two-sentences-to-discuss-the-answer}}

### Question 3. {{write-the-question}}
```
{{splunk query producing the table or graph below}}
```
![screenshot of a data table or a graph or both](image.png?raw=true) 

{{ write-one-or-two-sentences-to-discuss-the-answer}}
