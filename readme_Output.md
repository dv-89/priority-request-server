# priority-request-server

# output is below 
Enter no of requests = 10

Enter no of servers = 2

Enter max processing time = 6

Priority 1 is high and 5 is low.

Requests sorted by priority: 
Request 1 has priority 1 and time to process 5
Request 2 has priority 3 and time to process 2
Request 6 has priority 3 and time to process 6
Request 8 has priority 3 and time to process 5
Request 9 has priority 3 and time to process 3
Request 10 has priority 3 and time to process 5
Request 5 has priority 4 and time to process 3
Request 7 has priority 4 and time to process 4
Request 3 has priority 5 and time to process 3
Request 4 has priority 5 and time to process 2

Waitlist for each server : 
Server 0: ID=1
Server 0: ID=6
Server 0: ID=9
Server 0: ID=5
Server 0: ID=3

Server 1: ID=2
Server 1: ID=8
Server 1: ID=10
Server 1: ID=7
Server 1: ID=4

Server 0
processing Request with id 1 with priority 1 and time to process 5 sec
Server 1
processing Request with id 2 with priority 3 and time to process 2 sec

completed : 
Request 2 processed in 2 seconds by server1
Server 1
processing Request with id 8 with priority 3 and time to process 5 sec

completed : 
Request 1 processed in 5 seconds by server0
Server 0
processing Request with id 6 with priority 3 and time to process 6 sec

completed : 
 sh -c make -s
 ./main
Enter no of requests = 3

Enter no of servers = 2

Enter max processing time = 5

Priority 1 is high and 5 is low.

Requests sorted by priority: 
Request 2 has priority 2 and time to process 3
Request 1 has priority 3 and time to process 3
Request 3 has priority 3 and time to process 1

Waitlist for each server : 
Server 0: ID=2
 sh -c make -s
 ./main
Enter no of requests = 10

Enter no of servers = 2

Enter max processing time = 6

Priority 1 is high and 5 is low.

Requests sorted by priority: 
Request 1 has priority 1 and time to process 5
Request 2 has priority 3 and time to process 2
Request 6 has priority 3 and time to process 6
Request 8 has priority 3 and time to process 5
Request 9 has priority 3 and time to process 3
Request 10 has priority 3 and time to process 5
Request 5 has priority 4 and time to process 3
Request 7 has priority 4 and time to process 4
Request 3 has priority 5 and time to process 3
Request 4 has priority 5 and time to process 2

Waitlist for each server : 
Server 0: ID=1
Server 0: ID=6
Server 0: ID=9
Server 0: ID=5
Server 0: ID=3

Server 1: ID=2
Server 1: ID=8
Server 1: ID=10
Server 1: ID=7
Server 1: ID=4

Server 0
processing Request with id 1 with priority 1 and time to process 5 sec
Server 1
processing Request with id 2 with priority 3 and time to process 2 sec

completed : 
Request 2 processed in 2 seconds by server1
Server 1
processing Request with id 8 with priority 3 and time to process 5 sec

completed : 
Request 1 processed in 5 seconds by server0
Server 0
processing Request with id 6 with priority 3 and time to process 6 sec

completed : 
Request 8 processed in 5 seconds by server1
Server 1
processing Request with id 10 with priority 3 and time to process 5 sec

completed : 
Request 6 processed in 6 seconds by server0
Server 0
processing Request with id 9 with priority 3 and time to process 3 sec

completed : 
Request 10 processed in 5 seconds by server1
Server 1
processing Request with id 7 with priority 4 and time to process 4 sec

completed : 
Request 9 processed in 3 seconds by server0
Server 0
processing Request with id 5 with priority 4 and time to process 3 sec

completed : 
Request 7 processed in 4 seconds by server1
Server 1
processing Request with id 4 with priority 5 and time to process 2 sec

completed : 
Request 5 processed in 3 seconds by server0
Server 0
processing Request with id 3 with priority 5 and time to process 3 sec

completed : 
Request 4 processed in 2 seconds by server1

completed : 
Request 3 processed in 3 seconds by server0
Total execution time: 20.0011 sec
All requests processed.
