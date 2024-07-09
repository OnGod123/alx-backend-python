README
Async Tasks in Python
This project demonstrates the basics of asynchronous programming in Python using asyncio. The tasks involve creating and managing asynchronous functions to simulate delays and measure execution time.

Files
0-basic_async_syntax.py
Defines the wait_random coroutine:

Waits for a random delay between 0 and max_delay seconds.
Returns the actual delay.
3-tasks.py
Defines the task_wait_random function:

Returns an asyncio.Task that executes wait_random.
4-tasks.py
Defines the task_wait_n coroutine:

Spawns task_wait_random n times with the specified max_delay.
Returns a list of delays in the order they complete.
4-main.py
Test script:

Runs task_wait_n with specified n and max_delay.
Prints the list of delays.
