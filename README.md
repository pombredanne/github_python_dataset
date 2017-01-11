# GitHub Python dataset
============================
This dataset contains 21,631 Python repositories written by 3,895 users on GitHub.
The metadata (modules/packages information) of each repository is also included in this dataset.

1. list_repo_21631.txt
    - The list of repositories.

2. list_user_3895.txt
    - The list of users.

3. user_repo_commit.txt
   
    - Format : [user_index] [repo_index] [number of commits]
        a) user_index: each index i corresponds to the i-th user in list_user_3895.txt.
        b) repo_index: each index j corresponds to the j-th repository in list_repo_21631.txt.
        c) number of commits: the number of commits of user i on repository j.
    - Each field is split by a single space.

4. repo_api (a directory)
    - Each file name corresponds to a repository listed in list_repo_21631.txt.
    - The content in the file is the set of modules/packages used in that repository.

5. index.txt
    - Statistical data from repo_api


