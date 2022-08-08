
# Useful links
* https://docs.docker.com/compose/gettingstarted/

# Challenges
Please run the following as `ec2-user`, using sudo when required. 

## Challenge 1
Gain SSH access to the interviewInstance ec2 instance via its Public IP. You will need to use the AWS Console to retrieve connection details of the EC2 instance / aide in any required troubleshooting!!

## Challenge 2
On the interviewInstance -  Ensure docker is running, and list running containers.

## Challenge 3
Whilst on the interviewInstance - Inside users home directory, `clone` this repo

## Challenge 4 
Still on the interviewInstance - Inside your local copy of superapp there is a docker-compose file. 
  * Update the build to also install curl
  * Using `docker-compose`, `build` the superapp container. Fix any issues.
  * Using `docker-compose`, Bring the superapp container `up`. Ensure container stays up - fixing any issues along the way.
  * Exec into the superapp container and retrieve the value of environment variable `my_super_var`

## Challenge 5
As ec2-user commit and push changes, Use the commit message "Technical test - `your name`"


