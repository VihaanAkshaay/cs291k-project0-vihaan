# cs291k-project0-vihaan


### Questions to Answer:

##### On average, how many requests can ab complete in 10 seconds with all the power of two concurrency levels between 1 and 256 (i.e., 1, 2, 4, 8, 16, 32, 64, 128, 256)?

Concurrency Level: 1 Requests Completed: 204 \
Concurrency Level: 2 Requests Completed: 431 \
Concurrency Level: 4 Requests Completed: 1019 \
Concurrency Level: 8 Requests Completed: 2063 \
Concurrency Level: 16 Requests Completed: 3270 \
Concurrency Level: 32 Requests Completed: 4178 \
Concurrency Level: 64 Requests Completed: 4621 \
Concurrency Level: 128 Requests Completed: 4646 \
Concurrency Level: 256 Requests Completed: 4956 \

##### Why are there diminishing returns at higher concurrency levels?

Limitations on Server/ Limitations on bandwdth/ Establishing, Closing connection drags/ Queueing Times

##### What’s the performance difference when requesting HTTP and HTTPS?

Performance on http:

Concurrency Level: 1 Requests Completed: 492 \
Concurrency Level: 2 Requests Completed: 1193 \
Concurrency Level: 4 Requests Completed: 2171 \
Concurrency Level: 8 Requests Completed: 4425 \
Concurrency Level: 16 Requests Completed: 7686 \
Concurrency Level: 32 Requests Completed: apr_pollset_poll: The timeout specified has expired (70007) \
From these runs it is evident that HTTP takes way lesser time to run at the compromise of security.

##### How can github respond so quickly?

Github uses various techniques like caching, good infrastructure to share loads and requests, to achieve fast response times.

##### What is your site’s “Time to Interactive” according to PageSpeed Insights?

