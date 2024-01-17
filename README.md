# Ticket counter and stopwatch
A tool to count the tickets and time spent on each ticket.

![screenshot](https://github.com/doublezed2/counter-stopwatch/assets/5362615/0359d9b8-09e8-470a-9c65-ffba0fe91c98)

## Demo:
https://zubairzahid.com/counter-stopwatch/

## How to use:
**The Goal:**
- By default, 20 is the total number of tickets set up as the goal.
- You can click on **20** in the top right corner and set a new value.

**The Counter:**
- Click **+** to increment ticket counter
- Click **-** to decrement ticket counter
- Click **Reset** to set the ticket counter to zero

**The Progress Bar**
- The **Progress Bar** at the top will show how much percent you have completed the goal.

**The Stopwatch**
- When you start working on a ticket, start the stopwatch.
- You can pause the stopwatch with the **Pause** button.
- Click **Reset** to set the stopwatch to zero

## HTML Web Storage
- The Ticket Counter and the Goal use HTML Web Storage. This data will remain safe even after page refresh.
- The Stopwatch does not use HTML Web Storage, so it will reset to zero on page refresh.
