# Enterprise Linux Web Hosting Server

This project demonstrates how to set up a production-style Linux web server

## Technologies Used
Ubuntu Linux
Nginx Web Server
SSH
UFW Firewall
Cron JObs
Log Monitoring

## Architecture
Client Browser

Firewall (UFW)

Nginx Web Server

HTML Website


##Features Implemented 
Linux Server installation
Nginx web hosting
Firewall configuration
SSH secutity hardening
Automated backups using corn
log monitoring with /var/log/nginx/access.log


## Commands Used
### Install Nginx
sudo aptinstall nginx

### Start Nginx
sudo systemctl start nginx


### Enable Firewall
sudo ufw allow 80
sudo ufw enable


### Monitor Logs
sudo tail -f /var/log/nginx/access.log
 
