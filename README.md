# templeos-packer

## What is this?

This is a packer setup for making a TempleOS vagrant .box file.

## Building

`./packer-image-build.sh` produces a .box file in `./output/`.

## Running

See my Vagrant box file [at this link](https://app.vagrantup.com/henryfbp/boxes/templeos).

Or, run this:

```bash
mkdir templeos_vagrant
cd templeos_vagrant
vagrant init henryfbp/templeos
vagrant up
```

SSH will fail as TempleOS has no networking.

You need to then open VirtualBox, choose `1` for the HDD selection, and enjoy TempleOS.
