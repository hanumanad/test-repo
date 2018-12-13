 # Start with the ubuntu image
 FROM ubuntu:16.04
 
 #Install Git on the  Docker container
 RUN apt-get update && apt-get install -y git

 # Clone Git Hub repo 
 RUN git clone https://hanumanad:chintu-123@github.com/hanumanad/test-repo.git /tmp/test-repo

 #Install ansible on the  Docker container
 RUN apt-get update && apt-get install -y ansible

 # Copy Ansible file from git repo 
 #COPY /tmp/test-repo/install_apache.yaml /etc/ansible/

 # Run ansible playbook 
 RUN ansible-playbook /tmp/test-repo/step4/install_couchdb.yaml -c local
