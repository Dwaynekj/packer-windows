# Parallels Info

### Introduction

Install the packer plugin for vagrant [Vagrant-Parallels](http://parallels.github.io/vagrant-parallels/docs/installation/)

Use packer to build a vagrant-parallels box [Packer Vagrant Parallels](http://parallels.github.io/vagrant-parallels/docs/boxes/packer.html)

Use packer to build a parallels box [Packer Parallels](https://packer.io/docs/builders/parallels-iso.html)

Reference on using packer to build windows 7 [Packer Windows Reference](https://github.com/puphpet/packer-templates/blob/master/ubuntu-12.04-x86_64/template.json)

Build Parallels Provider
```
	packer build -only=parallels-iso template.json
```

For Vagrant RDP
Install
https://itunes.apple.com/en/app/microsoft-remote-desktop/id715768417?mt=12
then

```
	vagrant up
	vagrant provision
	vagrant rdp
```

For Vagrant SSH

```
	vagrant up
	vagrant ssh
```