# GitHub-Issue-Classification


The following list explains as in which order the artifacts should be executed:

1. bigquery_query.txt
1.1. Goto Google big query tool
1.2. Set the SQL dialect as legacy
1.3. Run the query provided in the "bigQuery.txt" text file on Google big query platform
1.4. Save the result as language_repo.csv


2. language_repo_fetch.ipynb
3. repo_issue_fetch.ipynb

4. Issue Classification.ipynb (Use GPU backend on Google Collab, this is the issue classification model)
