hugo-nginx-base
==================

Base Docker Image to run Nginx server to serve Hugo website


Usage
-----

Create a docker image based on this one.
Add your own nginx config in sites-enabled.

When you `git push` the ONBUILD commands will put the source in the right place, run hugo to generate the site and copy the contents to the nginx serving directory.

ORIGINAL DOCKERFILE was created by tutum, this is a radically changed clone of that.  Tutum makes some pretty slick docker images, check them out at github.com/tutumcloud
