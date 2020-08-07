# A Network That Trains At Zero Init
Here is a network that still trains with zero initilization.

Two weeks ago I had a job interview with ByteDance where I was asked about whether a zero initlized network can train? My answer was Yes and I fails the interview. Maybe I didn't make myself clear. 

To better illustrate my answer, I write this notebook to prove that a network can be trained when being zero initialized with proper supervision. 

The commom belief of zero initialized network cannot be trained relies on the assumption that shallow layers can only recive supervision from deep layers while deep layers can only revice information from shallow layers. Therefore when zero initialized, shallow layers recives zero or constant gradients while deep layers revices constant information.

However, a network can be designed to break such assumption and still performs better than random guess.
