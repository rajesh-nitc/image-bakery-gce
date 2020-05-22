## packer-pipeline

```.gitlab-ci.yml``` is included which automates the below manual steps
### validate packer template
```
cd packer
packer validate packer.json
```
### build image
```
cd packer
packer build packer.json
```
