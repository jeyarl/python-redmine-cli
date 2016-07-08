# Python redmine cli

Redmine command line interface


Usage: redm [options] hours comment

Options:  
  --version             show program's version number and exit  
  -h, --help            show this help message and exit  
  -a ACTIVITY, --activity=ACTIVITY  
                        activity in the time entry  
  -i ISSUE, --issue=ISSUE  
                        issue to work on  
  --times               no adding of time, but show current time entries in  
                        the issue  
  --issues              no adding of time, but show all issues assigned to me  
  -d DAYS_AGO, --days-ago=DAYS_AGO  
                        time spend on, relative to today by days ago (0 is  
                        today, 1 yesterday)  
  -w WEEKS_AGO, --weeks-ago=WEEKS_AGO  
                        time spend on, relative to today by weeks ago (0 is  
                        today, 1 is 7 days ago)  
  -c, --checkin         actually checkin the new log time in to the server    
