# Crack JIRA
java -jar atlassian-agent.jar -d -m <email> -n BAT -p jira -o http://<server-ip> -s <server-id>


# Install JIRA Service Desk
Administration --> Application --> Upload an application
Enter below URL and upload
https://marketplace.atlassian.com/download/apps/1213632/version/1040200001


# Crack JIRA Service Desk
java -jar atlassian-agent.jar -d -m <email> -n BAT -p jsd -o http://<server-ip> -s <server-id>