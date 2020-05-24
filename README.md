# Packer
To build VM images

```.gitlab-ci.yml``` is included which automates the below manual steps
## Validate Packer Template
```
cd packer
packer validate packer.json
```
## Build Image
```
cd packer
packer build packer.json
```
