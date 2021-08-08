# GitHub-Issue-Classification
GitHub  is  the  world’s  largest  version  control  and  source code  management  service  with more  than  50  million developers  worldwide. More than 100 million  repositories are publicly available which can be  mined  using  their  APIs. Data-driven analysis on usch repositories help to allocate resources towards project maintenance, improve productivity, project’s cost-effectiveness, and reduce the likelihood of bugs. In issue tracking systems developers can report tickets or potential problems, manage them and keep track of their progress. Similar to the other platform GitHub provides a issue tracker along with the labeling support. Accurate Classification  of  these  issue-reports can  help  monitor  the  software evolution  process  and  enable  better  tracking  for  various  industrial  stakeholders. Classification  of  issue  messages into   “bug-report”, “feature-request”,  and “enhancement” categories.



The following list explains as in which order the artifacts should be executed:
1. bigquery_query.txt
1.1. Goto Google big query tool
1.2. Set the SQL dialect as legacy
1.3. Run the query provided in the "bigQuery.txt" text file on Google big query platform
1.4. Save the result as language_repo.csv


2. language_repo_fetch.ipynb
3. repo_issue_fetch.ipynb

4. Issue Classification.ipynb (Use GPU backend on Google Collab, this is the issue classification model)
