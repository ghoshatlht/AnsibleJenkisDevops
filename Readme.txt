## Ansible-jenkins Devops ##

-----------------------------------------------------------

1. Install Jenkins in your system 

Go to the link https://jenkins.io/download/ for download. 

2. Set up Jenkins in your system and make a User

3. open your port for Jenkins Dashboard

  example: http://localhost:8080/ 

4. Dowload the Ansible-jenkins Devops folder from team drive, In Playbook folder there are job config file "Job_for_S2S_VPN.xml" 

5. Set your working directory according to your need

6. set the path of inventory file in ansible.cfg file and Edit the inventory file according to your need. 

7. Check the Jenkins Plug-in in Manage Jenkins 

    Ex: http://localhost:8080/manage & http://localhost:8080/pluginManager/

8. Configure your Jenkins according to your need. 

   Ex:http://localhost:8080/configure

9. Configure Global Security according to your need. 

   Ex:  http://localhost:8080/configureSecurity/

10. All set....

    go to your playbook directory

    Run playbook like 

    $ sudo ansible-playbook jenkins_service.yml -vvv
    and then
    for job build & Testing  
    
    sudo ansible-playbook Jenkins_job_build.yml -vvv

11. refresh the Jenkins Dashboard

Hope you will see the result. 

:)  

------------------------------------------------------------------------------------------------------------
    

     