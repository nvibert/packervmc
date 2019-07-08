# packervmc

Template of a working Packer template with VMware Cloud on AWS.

# Instructions
1) Download Packer for your platform
2) Download Jetbrains
3) Download the ISO you want to build the VM from and upload to WorkloadDatastore/ISO (create an ISO folder in the WorkloadDatastore). If you want to follow my example, download the Ubuntu ISO.
4) Download ubuntu-18.04-working template.json and preseed.cfg
5) Update the JSON file above with the right credentials and other settings, such as Network segment you want the VM to be attached.
5) Run the following command:

packer build ubuntu-18.04-working template.json

Watch the VM getting built !
