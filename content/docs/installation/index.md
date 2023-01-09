---
title: "Installation"
date: 2023-01-09T23:00:00Z
draft: false
weight: 1
---


## Homebrew

```sh
brew tap gravatalonga/ninja-lang
brew install ninja-lang
```  

## YUM / RPM

To enable, add the following file `/etc/yum.repos.d/ninja.repo`:

```sh
[ninja]
name=Ninja Programming Language
baseurl=https://yum.fury.io/gravatalonga/
enabled=1
gpgcheck=0
```  

Check if correctly created

```
yum --disablerepo=* --enablerepo=ninja list available
```  

To install you only need run following command:

```
yum install ninja-lang  
```  

## APT

To configure apt access, create a following file `/etc/apt/sources.list.d/ninja.list` with content of :

```  
deb [trusted=yes] https://apt.fury.io/gravatalonga/ /
```  

Or use this one line command:

```
echo "deb [trusted=yes] https://apt.fury.io/gravatalonga/ /" > /etc/apt/sources.list.d/ninja.list
```  

and them you can install

```
sudo apt install ninja-lang
```

## Windows  

For windows, you can get binaries from github.  

https://github.com/gravataLonga/ninja/releases  

## Manual Download

Download from [github](https://github.com/gravataLonga/ninja/releases)

## Manual Installation

```sh  
git clone https://github.com/gravataLonga/ninja
cd ninja
go build -o ninja-lang