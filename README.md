# Learn - 0.2 - RCS
## This Repo contains the solutions to the task given by Robotics Club of SASTRA for Python-Open CV training for the week 1(Learn-0.2)
### The link to the problem is <a href="https://github.com/Training-2024/Learn-0.2">given here</a>
<hr />
<p align="justify">
  We are required to write a python program which can process the given CSV file given and produce two outputs via two different functions producing a dictionary output from the given CSV file(marksheet) and the other producing another dictionary representing Grade Card which includes the grade calculated by taking the percentage of marks of all the five given subjects and assigning grades as a new key-value pair in the second dictionary.
  <br />
  <br />
  The required CSV file to be parsed is first read and then iterated using a for loop to obtain row wise values of the whole CSV file. There are actually two ways of reading a CSV file which is Normal reading and Dictionary reading. I used Dictionary reading because in that way its easy to reference the respective header of each elements of the row using the respective names. If normal reading is used, we need to access it like an array starting from 0 to n-1. 
</p>