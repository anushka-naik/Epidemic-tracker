# EPIDEMIC TRACER USING DSA 

Data structures used: 
- min heap
- graph implementation using adjacency list
- linked list
- hash tables

This is a program that allows the user to input values for each station or city and multiple stations can be connected with different paths relating each other.
The details of people at each station has to be manually entered on day 1. At the end of the day, a list of covid positive people will be released by user and this program 

1. backtrace and categorise each person into different statuses:
  i. quarantined
  ii. primary contact
  iii. secondary contact
  iv. not affected
The details of cause and source of infection as well as no of days of infection is kept a count of and people are free to travel and leave the quarantined station only 
after 14 days

2.It is an algorithm that provides 3 possible routes from source to destination: uses a variation of djikstra's algorithm to find shortest AND safest path; wherein priority is given to safety of the route to be offered to each traveller and if the risk of infection of each 2 or more paths is same, the distance is also taken into account.

3.It also provides the utility to check status of each station; most affected person in each station; infection probability of each station; etc

4.Allows you to check the status of each person since day 1.
