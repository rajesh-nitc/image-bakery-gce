# Packer
To build VM images

```.gitlab-ci.yml``` is included which automates the below manual steps
## Validate
Validate packer template
```
cd packer
packer validate packer.json
```
## Build
Build VM image with packer template 
```
cd packer
packer build packer.json
```
