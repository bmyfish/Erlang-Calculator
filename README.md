# Erlang-Calculator
Part 1:
It is an Erlang B calculator for the M/M/c/c "lost calls queuing model". The input parameters are the average arrival rate, lambda packets/min, the average service rate mu packets/min and the probability of blocking, PB. The output parameter is the number of servers required to satisfy the PB requirement. 
Part 2:
It is an Erlang C calculator for the M/M/c "delayed calls queuing model". The input parameters are the average arrival rate, lambda packets/min, the average service rate, mu packets/min. In addition, include input constraints on each of the following (separately and then collectively)
a) The probability that an arriving Packet will find all servers busy (i.e. P (W > 0)) should not exceed  where  is an input parameter epsilon
b) Given that an arriving packet must wait, the average waiting time should not exceed alpha minutes where alpha is an input parameter.
c) Less than beta% of all packets should have to wait more than gamma minutes for a free server where  and  are input parameters
The output of the calculator is the number of servers required to satisfy the above requirements/constraints. In addition, the calculator also provide the following averages: The average number of busy servers and the average number of packets in the system (both waiting and being served).
