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

### Restoring an old version of a file
git checkout --filename
- To revert to a version from a specific commit:
``````
git checkout dc9d8fac mental_health_survey.csv
``````
- For second to the last commit
``````
git checkout HEAD~1 mental_health_survey.csv
``````
### Restoring a repo to a previous state
``````
git checkout dc9d8fac
``````
- Alternatively
``````
git checkout HEAD~1