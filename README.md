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

Here is where you can locate the relevant files, nested within the `files/` directory

``` sh
.
├── files
│   ├── ansible
│   ├── configurations
│   │   ├── after
│   │   └── before
│   │       ├── vmx101.conf
│   │       ├── vmx102.conf
│   │       ├── vmx103.conf
│   │       ├── vmx104.conf
│   │       ├── vmx105.conf
│   │       ├── vmx106.conf
│   │       └── vmx107.conf
│   ├── docker
│   ├── docs
│   └── images
│       └── mpls-l3vpn.svg
├── LICENSE
└── README.md
```

As you can see, there is more to come later.

## Automation

We will be leveraging Ansible to provision our environment.