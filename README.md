# docker-playground

Vagrant-based image for Docker experiments

## Setup

Clone repository and start VM:

```
vagrant up
```

Once VM is built and provisioned (might take up to 10 minutes), reload:

```
vagrant reload
```

And SSH into the VM:

```
vagrant ssh
```

## Usage

Once VM is created, place your files under `share` directory, its going to
be linked into `/playground` on VM's filesystem.