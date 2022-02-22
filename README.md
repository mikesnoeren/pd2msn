# PD2MSN
The official PD2MSN repository.

This repository is based on the mikesnoeren/craft repository, which is an Craft CMS 3 scaffolding project using Tailwind and Alpine. 

**Please keep in mind:** This repository makes use of [TailwindUI](https://tailwindui.com/) which requires a paid licensed to use.

## Using mikesnoeren/pd2msn
The setup assumes you use [Lando](https://github.com/lando/lando), if you you use an alternative development environment please change the steps below accordingly.

### Copy the repository:
```bash
git clone https://github.com/mikesnoeren/pd2msn.git my-project
``` 

### Run it:
```bash
lando start && lando npm run watch
```

### Sync `node_modules` & `vendor` from container to host:
```bash
docker cp pd2msn_appserver_1:/app/vendor . && \
docker cp pd2msn_node_1:/app/node_modules .
```