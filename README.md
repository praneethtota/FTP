Overview:
This program is an implementation of multipath FTP in a given network. 

Given a network graph we create multiple FTP paths to increase the transfer speed of a large file. This causes the packets to get jumbled during transit 
as different paths have different delays. The jumbled packets require resources like buffer and compute power to rearrange them in the right order at the destination. 
Using this program we minimize the reources needed at the destination by intelligently routing packets across the different paths so that they reach the destination in 
right order (assuming a stable network ) 

Program reads an input file containing list of nodes in a graph (source, sink, capacity, delay) to first create a time delay network graph
and then create multiple optimal paths to minimize buffer needed at the destination to reconstitute the data.



