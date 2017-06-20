sa-grub
=======

[![Build Status](https://travis-ci.org/softasap/sa-grub.svg?branch=master)](https://travis-ci.org/softasap/sa-grub)

Medical role used to pin or unpin kernel to specific version

Example of use:

unpin previously pinned kernel version

```YAML

     - {
         role: "sa-grub"
       }

```

pin to specific version

```YAML


     - {
         role: "sa-grub",
         grub_pin_kernel_version: "Ubuntu, with Linux 4.4.0-79-generic"
       }


```



Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-grub  role using the command


`
   ansible-galaxy install softasap.sa-grub
`

the role will be available in the folder library/sa-grub

Please adjust the path accordingly.

```YAML

     - { 
         role: "softasap.sa-grub"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join Gitter channel at [Gitter] (https://gitter.im/softasap/)

