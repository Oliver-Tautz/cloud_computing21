## Distance learning

* https://dl.bi.denbi.de

## Openstack

* open `credentials.txt` in distance learning and use credentials to login on
* openstack.cebitec.uni-bielefeld.de

## Openstack cmd

* `source /vol/cloudcomputing/openstack/bin/activate`: activate python env with openstack installed
* `source CloudComputing-openrc.sh` to add credentials. Download script from openstack ui

## Object Storage

* `openstack ec2 credentials create` to create new credentials
* `mc host add $Container https://openstack.cebitec.uni-bielefeld.de:8080 $access $secret`

## Volumes

* `sudo mount $vol $mountpoint` to mount volume on mountpoint 
* `sudo chown $user:$group $folder` change ownership of folder


