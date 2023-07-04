# TakkehPerformance
-To execute this JMX you need to download and install Jmeter, clone this repo
-the second JMX with name TakkehWithoutFilter.jmx doesn't have the thread number and itiration number which make the graphs and the statistics 
on every request counted on the whole samples
-this JMX is designed to run on 8 users concurrently and repeat this cycle 10 times(iterations) 
and the next iteration can't start till the current one completly finish
- you can increase the number of iterations as much as you can.
- to increase the number of concurrent threads you have to create user and driver then add them data in the attached data file
- *before excution* disable cycle execution thread group and enable store login thread group and run
- extract the store access token from the results and add it in the StoreToken parameter in user define variable file
- Disable store login thread group and enable Cycle execution and run
- observe the results from View result tree in case you run with Takkeh.jmx and from aggregation report in case you run TakkehWithoutFilter.JMX
