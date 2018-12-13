 # A Docker file is created to perform the below steps
   1. Build a Docker container of ubuntu
   2. Install Git on Docker container
   3. Clone my Git repo where all my code is checked-in
   4. Install Ansible on Docker conatiner
   5. Run the Ansible play book (which is checkedout from Git repo)to perform the below
      5.1 Install couch DB on Docker container
 Note : Enabled port 5984 on my AWS security groups to access it from external machines 

 # A Docker compose file (docker-compose.yml)is written to bring the Docker container UP
  To run the Docker compose file execute the below command
  # docker-compose up

 Note : Log file of the above executing is also attached File Name = Docker_compose.log
  
