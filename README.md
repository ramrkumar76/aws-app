Create a keypair in AWS
Run cloudformation to create nginx/apache server and the cloudformation sets up the reverse proxy. Once finished just hit the NGINX server URL which renders the apps from Tomcat.
virtual.conf on nginx is set up to make nginx server act as reverse proxy in the UserData of Nginx.
