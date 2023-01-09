# 0x01. Python - Async


---

### [0. The basics of async](./0-basic_async_syntax.py)
* Write an asynchronous coroutine that takes in an integer argument (max_delay, with a default value of 10) named wait_random that waits for a random delay between 0 and max_delay (included and float value) seconds and eventually returns it.


### [1. Let's execute multiple coroutines at the same time with async](./1-concurrent_coroutines.py)
* Import wait_random from the previous python file that you’ve written and write an async routine called wait_n that takes in 2 int arguments: max_delay and n. You will spawn wait_random n times with the specified max_delay.


### [2. Measure the runtime](./2-measure_runtime.py)
* From the previous file, import wait_n into 2-measure_runtime.py.


### [3. Tasks](./3-tasks.py)
* Import wait_random from 0-basic_async_syntax.


### [4. Tasks](./4-tasks.py)
* Take the code from wait_n and alter it into a new function task_wait_n.  The code is nearly identical to wait_n except task_wait_random is being called.
