# appnexus-demo [![Build Status](https://travis-ci.org/totem/appnexus-demo.svg)](https://travis-ci.org/totem/scholastic-demo)
Totem demonstration for Appnexus

# Demo Steps

* The lasted deployed version can be accessed using:  
[https://appnexus-demo.elb.us-west-1.cu.melt.sh](https://appnexus-demo.elb.us-west-1.cu.melt.sh)
* Login to github and [fork](https://github.com/totem/appnexus-demo/fork) this repository.
* Modify file [demo/views.py#Line 10](demo/views.py#L10) and fix the typo for "Worlb!" to "World!"
* Modify file [Dockerfile#Line 1](Dockerfile#L1) and change python image from 2.7-trusty to 3.4-trusty
* Create a [pull request](https://github.com/totem/appnexus-demo/compare) to merge these changes.
