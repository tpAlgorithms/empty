empty repo for tp.mail.ru students review-board submisions

usage:

goto your working dir:
$ cd my_source_directory

add this repo as remote branch:
$ git remote add tp_empty git://github.com/tpAlgorithms/empty.git

add your source files to index
$ git add my_solution.cpp

to generate diff: 
$ git diff --cached > my_solution.cpp.diff


Now You can create a new review board request on http://tp-test1.corp.mail.ru:81/reviews/
select tpAlgorithms/empty ass base repository

Here is the tutorial for ReviewBoard http://www.reviewboard.org/docs/manual/dev/users/


there are many alternative ways to creaete valid difs...

it's far more convinient to use post-review tool
learn ho to: http://www.reviewboard.org/docs/manual/dev/users/tools/post-review/


PS. This resource is for students affilated with tp.mail.ru
Plase. don't use  the service if You are not enrolled
