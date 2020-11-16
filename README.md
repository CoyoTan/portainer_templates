# portainer_templates
A list of templates used by the Coyotech Portainer server!

At this time, development to this listing has stopped. Portainer CE 2.0 does not support the needed components to continue, docker-compose V3 support. Portainer CE 2.1 is mapped out to provide this compatibility, at which point this project will continue.

##TODO:
1) Reminder: Be prepared to reformat portainer.json. When Portainer CE 2.1 comes out with support for Docker-compose v3, things will most certainly change.
2) Docker-compose files are NOT complete.
  a) Remember to find a way to replace volumes with "anonymous" volumes to allow for multiple stacks of the same container, but provide different data volumes.
  b) Read A. Make random generated volume names. This might not be an issue if CE 2.1 has good support options for v3 compose.

# Reference Material
https://github.com/Qballjos/portainer_templates/blob/master/Template/Stack/bookstack.yml
https://raw.githubusercontent.com/Qballjos/portainer_templates/master/Template/template.json
https://raw.githubusercontent.com/portainer/templates/master/templates-2.0.json
https://portainer.readthedocs.io/en/stable/templates.html
https://docs.docker.com/engine/reference/commandline/volume_create/#driver-specific-options
