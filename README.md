# GDSC NSEC MatterMost
We at GDSC Use our own hosted Slack Alternative and Task Board.
We use a self hosted MatterMost instance for our Slack Alternative and a self hosted Taiga instance for our Task Board.
It is hosted on our own server and is accessible only to GDSC members.

# To Run on Local:
`docker-compose -f docker-compose.yml -f docker-compose.without-nginx.yml up -dup -d`
