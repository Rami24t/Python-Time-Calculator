# Scientific Computing with Python: Build a Time Calculator Project

## [This](https://github.com/Rami24t/Python-Time-Calculator/blob/main/time_calculator_project.py) is [my solution](https://github.com/Rami24t/Python-Time-Calculator/blob/main/time_calculator_project.py) to the following Build a Time Calculator Project

#### Build a Time Calculator Project
#### One of the required certification projects from freeCodeCamp's 'The Scientific Computing with Python (Beta)' curriculum which aims to equip programmers with the skills to analyze and manipulate data using Python, a powerful and versatile programming language and to practice key concepts like scientific computing, data structures, algorithms, ... and to perform complex calculations using a variety of tools.


Write a function named add_time that takes in two required parameters and one optional parameter:

- a start time in the 12-hour clock format (ending in AM or PM)
- a duration time that indicates the number of hours and minutes
- (optional) a starting day of the week, case insensitive

The function should add the duration time to the start time and return the result.

If the result will be the next day, it should show (next day) after the time. If the result will be more than one day later, it should show (n days later) after the time, where "n" is the number of days later.

If the function is given the optional starting day of the week parameter, then the output should display the day of the week of the result. The day of the week in the output should appear after the time and before the number of days later.

Do not import any Python libraries. Assume that the start times are valid times. The minutes in the duration time will be a whole number less than 60, but the hour can be any whole number.

## The following are some examples of different cases that [my solution code](https://github.com/Rami24t/Python-Time-Calculator/blob/main/time_calculator_project.py) handles.
```
add_time('3:00 PM', '3:10')
# Returns: '6:10 PM'

add_time('11:30 AM', '2:32', 'Monday')
# Returns: '2:02 PM, Monday'

add_time('11:43 AM', '00:20')
# Returns: '12:03 PM'

add_time('10:10 PM', '3:30')
# Returns: '1:40 AM (next day)'

add_time('11:43 PM', '24:20', 'tueSday')
# Returns: '12:03 AM, Thursday (2 days later)'

add_time('6:30 PM', '205:12')
# Returns: '7:42 AM (9 days later)'

add_time('3:30 PM', '2:12')
# Returns: '5:42 PM'

add_time('11:55 AM', '3:12')
# Returns: '3:07 PM'

add_time('2:59 AM', '24:00')
# Returns: '2:59 AM (next day)'

add_time('11:59 PM', '24:05')
# Returns: '12:04 AM (2 days later)'

add_time('8:16 PM', '466:02')
# Returns: '6:18 AM (20 days later)'

add_time('3:30 PM', '2:12', 'Monday')
# Returns: '5:42 PM, Monday'

add_time('2:59 AM', '24:00', 'saturDay')
# Returns: '2:59 AM, Sunday (next day)'

add_time('11:59 PM', '24:05', 'Wednesday')
# Returns: '12:04 AM, Friday (2 days later)'

add_time('8:16 PM', '466:02', 'tuesday')
# Returns: '6:18 AM, Monday (20 days later)'
```
