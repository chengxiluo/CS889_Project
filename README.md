## Dependencies

- python3.7
- torch1.2
- numpy
- tqdm
- sklearn
- pickle


## Command to run

python example.py 0 0 --num 3

First parameter is user type. 0: simulated users, 1:real users.

Second parameter is agent type. 0: rule-based method, 1: RL-based method.

Third parameter (optional) is the number of conversation round, default is 1. 

note: when user type is real users, target restaurant information is provided and users have to answer questions from the system based on these information.




