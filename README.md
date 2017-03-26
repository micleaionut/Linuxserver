1.I've used digital ocean private server to create a Linux server.
3. Update all currently installed packages.
4. Change the SSH port from 22 to 2200.
5. Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).

Give grader access.

6. Create a new user account named grader.
7. Give grader the permission to sudo.
8. Create an SSH key pair for grader using the ssh-keygen tool.

9. Configure the local timezone to UTC.
10. Install and configure Apache to serve a Python mod_wsgi application.
11. Install and configure SQLAlchemy:
   

12. Install git.

13. Clone and setup your Item Catalog project from the Github.

IP : 192.241.132.194
Passprase: udacity
user: grader
SSH Key attached: udacity file


https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps