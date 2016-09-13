# Code for working through the book Docker in Action

Just for remembering the workflow. Can be helpful in the future.

Some commands:
`docker stop $(docker ps -a -q)` -- stop all running containers
`docker volume ls -qf dangling=true` -- list all abandoned volumes
`docker rm $(docker volume ls -qf dangling=true)` -- remove all the abandoned volumes