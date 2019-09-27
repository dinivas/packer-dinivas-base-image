# Packer Dinivas base image

This __packer__ project build and upload `Dinivas` Base image used for all other `Dinivas` components.

```sh
packer build  -var 'ssh_user=XXXX' -var 'source_image_id=XXXXXXX' -var 'flavor=XXXXXX' template.json
```


## Variables

You can override the followings variables

```
    "image_name": "Dinivas Base Centos7",
    "image_tags": "dinivas,centos,base",
    "image_min_disk": "5",
    "image_visibility": "public"
```