Task management system
==================================

There are some complicated operations or things that need take a long time in our system now.when many user use this function at the same time .Our system load will be very high.To reduce this condition.we make a general class named **Task**,we make this complicated things as a task and system handle the task in a task pool.To reduce the system stress.

## Task Class
### Property things


* *Status*: running status ,start end running waiting suspend
* *Time*: start time end time some thing else
* *Name*: task name.
* *Context*: data needed for this task


### function things

* *start/stop/suspend/cancel*: some operation

## TaskManager Class
manage task poll and task queue


* make a interface for admin/user to see the system task running status
