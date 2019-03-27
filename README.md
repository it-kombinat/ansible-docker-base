<p><img src="http://1000logos.net/wp-content/uploads/2017/07/Logo-Docker-500x394.jpg" alt="docker logo" title="docker" align="right" height="60" /></p>

Ansible-Role-Splunk
=========

Deploy Splunk Container

Requirements
------------

 - Ansible >= 2.4
 - Docker and docker-py

Role Variables
--------------


| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `spl_container_name` | splunk-demo  | Name of the Container |
| `spl_docker_image` | splunk/splunk:latest | Docker Image (incl.tag) |
| `spl_admin_password` | demo0815 | Splunk Admin Password|


Author Information
------------------

## Author Information

You can find me on Twitter: [@itkombinat](https://twitter.com/itkombinat)
