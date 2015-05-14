# why should you care about docker?

---

## lots of smaller services

* bigger operational overhead
* trickier to run locally

---

# what problems? 
(and potential solutions without docker)

---

## it works on my machine
* you can just get a developer VM
* needs beefy dev machines
* slow startup and big VM images

---

## configuration managament
* Puppet/Chef/etc has to ensure state is correct
* every single time!

---

## packaging
* just build a deb/rpm package - fpm
* you know what f stands for, right?

---

# docker

---

## docker vs VMs

* just do an [image search](https://www.google.co.uk/search?q=docker+vs+vms&tbm=isch)
* lightweight, less overhead

---

## docker images

* union filesystem and caching
* immutable (shareable!) layers
* base images FTW

---

## docker registry

* docker images to deploy code instead of packages
