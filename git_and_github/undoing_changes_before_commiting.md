### Unstaging a single file in Git
- To unstage a single file:
``````
git reset HEAD summary_statistics.csv
``````
``````
nano summary_statistics.csv
``````
``````
git add summary_statistics.csv
``````
``````
git commit -m "Adding age summary statistics
``````
### Unstaging all files
``````
git reset HEAD
``````