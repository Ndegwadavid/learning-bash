Cron is a job scheduling utility present in Unix like systems. You can schedule jobs to execute daily, weekly, monthly or in a specific time of the day. Automation in Linux heavily relies on cron jobs.


Example: 
## * * * * * sh /path/to/script.sh

Examples of cron jobs 

## SCHEDULE	    SCHEDULED VALUE

5 0 * 8 *	    At 00:05 in August.
5 4 * * 6	    At 04:05 on Saturday.
0 22 * * 1-5	At 22:00 on every day-of-week from Monday through Friday.

more here (https://www.freecodecamp.org/news/cron-jobs-in-linux/)

How to Check Existing Scripts in a System
Using crontab
## crontab -l 
lists the already scheduled scripts for a particular user.