# Conference Room Schedule System 
Here I implement an application about <strong> Conference Room Schedule System </strong> . It is a classic application of this problem is in
scheduling a room for multiple competing events, each having its own time requirements (start and end time). <br>
Suppose we have a set of activities {a 1 ; a 2 ; … ;a n } that wish to use a resource, such as a Conference Room , 
which can serve only one activity at a time.  <br>
Each activity a i has a start time s(i) and a finish time f(i) , where 0 s(i) < f(i) < α.
We have to select the maximum size subset of activities that are mutually compatible. Two activities are compatible if their intervals do not overlap. <br>
Here we use <strong> Greedy Algorithm </strong>
<br>

![Screenshot (852)](https://user-images.githubusercontent.com/64780532/120160344-fb3c4700-c217-11eb-9656-8c4d053995c4.png)
<br>

## Explanation
At first we input how many event we want to arrange. Here negetive number is an invalid input. 
After that we input start times and ending times from 0 to 23 because a day has 24 hours and our Conference Room is 24 hours open.
After valid input this application suggest you the maximum size subset of activities that are mutually compatible.

<h2> Thank You!  </h2>
