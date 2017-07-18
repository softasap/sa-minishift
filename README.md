sa-minishift
============

[![Build Status](https://travis-ci.org/softasap/sa-minishift.svg?branch=master)](https://travis-ci.org/softasap/sa-minishift)

Simple

```YAML
  roles:
    - {
        role: "sa-minishift"
      }
```

Advanced:


```YAML
  roles:
  - {
      role: "sa-minishift"
    }
```


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-minishift  role using the command


`
   ansible-galaxy install softasap.sa-minishift
`

the role will be available in the folder library/sa-minishift

Please adjust the path accordingly.

```YAML

     - { 
         role: "softasap.sa-minishift"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join Gitter channel at [Gitter] (https://gitter.im/softasap/)
