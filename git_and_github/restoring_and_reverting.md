To find commit we want to revert to, we use
``````
git log
``````

We can restrict the number of commits displayed using -
``````
git log -3
``````
To look at commit history of one file
``````
git log -3 report.md
``````
Restrict git log by date
``````
git log --since='Apr 2 2022'
``````