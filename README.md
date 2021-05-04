# Initial

# Table of Contents
- [Initial](#initial)
- [Table of Contents](#table-of-contents)
- [System-Engineering](#system-engineering)
- [Please implement exercise below](#please-implement-exercise-below)
  - [Build sample laravel(php framework) site](#build-sample-laravelphp-framework-site)
  - [Please implement for mysqldump backup shell(shell script)](#please-implement-for-mysqldump-backup-shellshell-script)
  - [Build your application to container images and manage your service with docker-compose](#build-your-application-to-container-images-and-manage-your-service-with-docker-compose)
  - [Upload your git repository to public github and must have content below](#upload-your-git-repository-to-public-github-and-must-have-content-below)

# Please implement exercise below
## Build sample laravel(php framework) site
- php required package: php7.4,php7.4-fpm,php7.4-mysql
- sql server: mysql-5.7
- web server: nginx
- please config nginx and add new site for laravel default page
- virtual hostname: heyu.site

## Please implement mysqldump backup shell(shell script)
- Import sample database data to mysql:https://github.com/datacharmer/test_db
- use sed & awk to dump every database for mysql backup
- backup file name: mysql-(%Y%m%d%H)-database_name.tar.gz
- Delete Backupfiles older than 10 days using shell script

## Build your application to container images and manage your service with docker-compose
- Dockerfile
- docker-compose.yml

## Upload your git repository to public github and must have content below
``` shell
app                   # application location
.env.example
Dockerfile
docker-compose.yml
README.md             # How to use
```
# Note
### We will clone your git repository and verify in local dev environment
