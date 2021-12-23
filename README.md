# MPLS L3VPN with Ansible

An EVE-NG lab based on an MPLS L3VPN service provider network running Juniper vMX routers.

## Lab Topology

Routing technologies used

- IS-IS
- iBGP
- MPLS
- RSVP

[![N|Solid](./files/images/mpls-l3vpn.svg)](https://juniper.net/)

## Project Layout

Here is where you can locate the relevant files nested within the `files/` directory. Many of these components are still being worked on.

``` sh
`--> tree
.
├── files
│   ├── ansible
│   ├── configurations
│   │   ├── after
│   │   │   ├── amarillo.conf
│   │   │   ├── austin.conf
│   │   │   ├── dallas.conf
│   │   │   ├── elpaso.conf
│   │   │   ├── fortworth.conf
│   │   │   ├── houston.conf
│   │   │   └── sanantonio.conf
│   │   └── before
│   │       ├── amarillo.conf
│   │       ├── austin.conf
│   │       ├── dallas.conf
│   │       ├── elpaso.conf
│   │       ├── fortworth.conf
│   │       ├── houston.conf
│   │       └── sanantonio.conf
│   ├── docker
│   ├── docs
│   ├── eveng
│   │   └── lab.zip
│   └── images
│       └── mpls-l3vpn.svg
├── LICENSE
└── README.md

9 directories, 18 files

```

## Automation

We will be leveraging Ansible to provision our environment.