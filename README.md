# GitLab Sysops Repository
When u need to create repository of files in gitlab from multiple hosts.
What script doing:

 - script create groups, projects and user in gitlab
 - create deploy.sh script
Execute bash repository.sh on remote host, script grab files from list repository.list and commit & push to gitlab project

Description of hosts file:
10.100.100.100\telastic\tpdc\tnode1\tElasticsearch\telasticsearch\tProduction\tproduction

 - first 4 rows, define user/project name
 - all other define as first pretty name and secod path name of group
