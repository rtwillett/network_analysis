# Network Analysis Exploration

Working remotely during the pandemic, my internet connection went through a period of significant disruption where I could not even access DNS servers and essentially dropped off the internet completely with high frequency. I started collecting ping data on a raspberry pi and started writing a notebook as a means of trying to hone in on the nature of the disfunction.

### Results
Ultimately I found that my ping latency was very low but looking at a rolling average of the difference in timestamps of successfully returned pings, I found that my connection was dropping off the network. The issue was identified as a signal integrity issue on the drop at the street. 

### Future Development
This repo will stand as a sandbox for me to explore various concepts in network analysis.
