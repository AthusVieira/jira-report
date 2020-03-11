### Usage

User email and access token are the only required option:
You may need to add this on your Path env variable (Windows users)

`jira-report generate [-u | --user] <user.email@email.com> [-t | --token] <AccessToken>`

Other options are available:

```
-p or --project : specify the project name
-a or --assignees : Set the assignee you are searching for.
                    You can specify many option to search for many assignees
--from : Start searching resolved issues from this date
--to : Stop searching resolved issues on this date.
-l or --max : The amount of data to fetch from Jira API since they use it to improve performance
-o or --out : The absolute path you want to save your generated report     
```

#### Important Note:

I assume that the resolved issues are the issues whose status is one of these: DONE, CLOSED, DEPENDENT, READY FOR MIGRATION, READY FOR QA or MIGRATED 

Bugs or other suggestion, please send me an email at athusvieira@gmail.com

Thanks!
