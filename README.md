# FortigateCloud

This lab will configure and install fortigate firewall and a client should be conneting to it via PVC

Prerequisite: Registered Azure account

First head to marketplace, search for fortigate and select "Fortinet Fortigate Next-Generation Firewall"

Then select "single VM" and hit create

If you have a resourse group you should create one. In our case its "HomeLab". Select desired region, username, password, Fortigate name prefix. Change image version to latest. Keep everything els default

Leave everything in Instance at default

At the network section there has been networks created by default. Change this if you which. The only change we do here is by disable accelerating network

In public ip section, you can leave the IP address as default, SKU: Basic, Assignment: Dynamic

In advanced select No on serial console
