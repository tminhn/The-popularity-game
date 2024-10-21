<h3 align="center">
<p>Project for IFT6504 - Mathematical Programming
</h3>
This is a final project for the course IFT6504 - Mathematical Programming, offered at University of Montreal.
<h3 align="center">
<p>Abstract
</h3>
In recent years, streaming services have become increasingly popular, revolutionizing the way people
consume media such as movies, TV shows, and music. This trend can be attributed to several factors
such as the increasing availability and accessibility of high-speed internet, the growing demand for
personalized and on-demand content, and the convenience and affordability offered by streaming
services. The COVID-19 pandemic has further accelerated the growth of streaming services as
people spent more time at home and turned to streaming to keep themselves entertained. The demand
for streaming services has also led to the emergence of new players. As a result, the market for
streaming services has become highly competitive, with numerous players vying for a share of the
market. We want to model this competition in the form of a Nash game among Stackelberg players.
Each player solves a Stackelberg game where a streaming service, as a leader, wants to maximize
its profit while its subscribers, as the followers, want to maximize their utilities. For the leader’s
problem, the objective function will depend on its subscription price that is fixed for simplification,
the number of subscribers, and its spending to increase the quality of service such as original content
production. On the other hand, each follower will face a knapsack problem where the goal is to
choose the services that maximize the total utilities, given a certain budget. The utilities can be
subjective to different groups of audiences. Because of the nature of this game, all the leaders are
sharing a pool of followers, and a follower can subscribe to many leaders. We also assume that the
followers do not compete or interact with each other. Intuitively, the leaders will want to gather as
many followers as they can by investing more on their quality. This strategy decreases the objective
function at first but it is expected to increase the subscribers and the profit in the long run. Our
approach to solve this game is to implement a cutting plane method then solve for the best responses
of leaders sequentially in the form of reformulated value function. There are three possible solutions
for our algorithm: a Nash equilibrium where no leaders want to change their best responses, a local
equilibrium that we define specifically for this game, and a case when no equilibrium found that can
potentially provide some insights into the competition.
<br>
<br>
The report of this project, formatted as a paper, can be found [here](./IFT6504_Project_Report.pdf), along with the [tutorial](./IFT6504_Project_Tutorial.html).
