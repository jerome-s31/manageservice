# manageservice
manage service available on REH servers
Calling with the following playbook : 
ansible-playbook -i inventory/$yourInventory playbook/manageServices-jeje.yml --tags "os,httpd,tomcat,webu,eventservice,elastic,logstash,kibana,nginx,addin,backa,polla,redis" --extra-vars="variable_host='manage-service' variable_actionTodo='status'"

tags contains the managed service : 
 - os
 - httpd
 - tomcat
 - webu
 - eventservice 
 - elastic
 - logstash
 - kibana
 - nginx
 - addin
 - backa
 - polla
 - redis
variable_actionTodo can be : 
 - status
 - start
 - stop
 
