# GitHub Python dataset
============================
This dataset contains 21,631 Python repositories written by 3,895 users on GitHub.
The full lists of users and repositories are based on the events on GitHub until October 21, 2016.
The metadata (modules/packages information) of each repository is also included in this dataset.

1. list_repo_21631.txt
    - The list of repositories.

2. list_user_3895.txt
    - The list of users.

3. user_repo_commit.txt
   
    - Format : [user] [repo] [number of commits]
        + user: each user i corresponds to one of the users in list_user_3895.txt.
        + repo: each index j corresponds to one of the repositories in list_repo_21631.txt.
        + number of commits: the number of commits of user i on repository j.
        + Each field is split by a single space.

4. repo_api (a directory)
    - Each file name corresponds to a repository listed in list_repo_21631.txt.
    - The content in the file is the set of modules/packages used in that repository.

5. index.txt
    - Statistical data from repo_api
    
6. top30.txt

    - Format : [ranking] [user]
        + user: the top 30 users in the dataset.
        + ranking: the actual ranking of user based on the ranking on <a href="http://github-awards.com/">Git Awards</a>.


