 # A Docker file is created to prform the below steps
   1. Build a Docker container of ubuntu
   2. Install Git on Docker container
   3. Clone my Git repo where all my code is checked-in
   4. Install Ansible on Docker conatiner
   5. Run the Ansible play book (which is checkedout from Git repo)to perform the below
      5.1 Install Apache on Docker container
      5.2 Copy my HTML from my Git repo to /var/www/html
      5.3 Restart apache using ansible script

 # A Docker compose file (docker-compose.yml)is written to bring the Docker container UP
  To run the Docker compose file execute the below command
  # docker-compose up

 Note : Log file of the above executing is also attached
  
