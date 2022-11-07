# cigen-community-templates

These templates are simply Cloud-Init `user-data` files that have been parametized so they can be regex'd via [envsubst](https://linux.die.net/man/1/envsubst).

> These templates DO NOT currently work for creating Ubquity auto-install files.


## Templates

1. [**ansible-boilerplate**](ansible-boilerplate.yaml): *A base-system capable of running ansible profiles from the similarly-named [ansible-boilerplate](https://github.com/cloudymax/ansible-boilerplate) repo.*

2. [**game-ci-vdi**](game-ci-vdi.yaml): *A virtual desktop environment for Unity3d with Editor and Hub.*

3. [**gitlab-runner**](gitlab-runner.yaml): *create a self-hosted gitlab runner.*

4. [**scrap-metal-auto-install**](scrap-metal-auto-install.yaml): *replicates the bare-metal system image for Scrap-Metal as a VM.*

5. [**slim**](slim.yaml): *creates a minimal system image with users, ssh-keys and updated package-cache only.*
