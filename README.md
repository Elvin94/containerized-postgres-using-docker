# containerized-postgres-using-docker
Running postgres on docker using LinuxONE Communit Cloud


## Prerequisites
 1. Request access to LinuxONE Community Cloud. Follow instructions [here](https://github.com/Elvin94/LinuxONE-OSS-CC)


### Step 1: Install docker
 
   1.1 Install postgresql
   
   For RHEL: 
   ```sh
   # sudo yum install docker
   ```
   For SLES:
   ```sh
   # sudo zypper install docker
   ```
   1.2 Ensure that docker is installed
   Both RHEL and SLES
   ```sh
   # docker version
   ```
   ![alt text](images/docker_version.png "Check /data disk")

### Step 2: Install postgres database server on LinuxONE Community Cloud
 
   1.3 Install postgresql
   
   For RHEL: 
   ```sh
   # sudo yum install postgresql-server
   ```
   For SLES:
   ```sh
   # sudo zypper install postgresql-server
   ```
   
  ### Step 2: Install postgres database server on LinuxONE Community Cloud
