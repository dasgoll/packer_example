memo
====

 * if you do not set "access_key", the environmental variable "AWS_ACCESS_KEY_ID" or "AWS_ACCESS_KEY" will be used.
 * if you do not set "secret_key", the environmental variable "AWS_SECRET_ACCESS_KEY" or "AWS_SECRET_KEY" will be used.

installation
============
 1. install berkshelf (comes installed with ChefDK)
 2. create Berksfile (will be generated when you run *chef generate cookbook cookbooks/mycookbook*)
 3. berks vendor vendor-cookbooks
 4. packer build build_sa_east_1.json
