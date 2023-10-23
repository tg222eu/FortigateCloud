# FortigateCloud

This lab will configure and install fortigate firewall and a client should be conneting to it via PVC

Prerequisite: Registered Azure account

First head to marketplace, search for fortigate and select "Fortinet Fortigate Next-Generation Firewall"

Then select "single VM" and hit create

If you have a resourse group you should create one. In our case its "HomeLab". Select desired region, username, password, Fortigate name prefix (VM host name). Change image version to latest. Keep everything els default. If you are using a license free / trial version then make sure that you are using 1 cpu and 1gb RAM

Leave everything in Instance at default

At the network section there has been networks created by default. Change this if you which. The only change we do here is by disable accelerating network

In public ip section, you can leave the IP address as default, SKU: Basic, Assignment: Dynamic

In advanced select No on serial console and finish

The deployment will take some time to complete.

Once deployment is complete, you can now go into virtual machine Fortigate-FGT and check the public address. This address will let you connect to the firewall with PVC. Copy the address and paste it in your browser, make sure you begin with use https://

Once logged in fortigate ask for a license. If you dont have a license select Evaluation License and enter your Forticare account Upload the licens file and proceed

Fortigate Setup: Later
