# gerbils

A local Jekyll blog, run from a FreeNAS jail, where posts are simple stories in large type for a kindergartner who is just starting to read.

## Prerequisites

* Hardware: a [very basic FreeNAS 9.2.0 setup](http://www.enoriver.net/freebsd/2014/01/11/freenas-works-as-advertised/).
* Software: 
  1. A [port jail](https://github.com/TwilightCoders/FreeNAS-Rails-Setup) that acts as a web server. Follow, in this order, the instructions at 
    - 1 (Jail), 
    - 1.1 (SSH), 
    - 1.1.1 (adduser), 
    - 1.2 (Ports), 
    - 1.2.1 (bash), 
    - 1.2.2 (sudo),
    - 1.2.3 (git),
    - 1.2.10 (ruby),
    - 1.2.6 (node)
  2. Ruby gems:
    ```
    cd /usr/ports/devel/ruby-gems;
    make install clean
    ```
  3. [Jekyll](http://jekyllrb.com/). You can start with a brand new blog as shown in the quick start instructions, or clone mine and modify to suit. 
 
