general
=======

General

Update git commit author

git filter-branch -f --env-filter "GIT_AUTHOR_NAME='Nick Blumenthal'; GIT_AUTHOR_EMAIL='nrblum01@gmail.com'; GIT_COMMITTER_NAME='Nick Blumenthal'; GIT_COMMITTER_EMAIL='nrblum01@gmail.com';" HEAD
