# INSTALL FROM SOURCE
installing from source will get you the latest version of git - - UI enhancements
if you are using a distro which is relatively old to te current ones and contains old packages 
installing from source is the best.

## 1> DEPENDENCIES FIRST:
### debian :
``
$ apt-get install libcurl4-gnutls-dev libexpat1-dev gettext \
libz-dev libssl-dev
``

### fedora :
``
$ yum install curl-devel expat-devel gettext-devel \
openssl-devel zlib-devel perl-devel asciidoc xmlto
``

## 2> grab latest git snapshot
`
http://git-scm.com/download
`

## 3>compile and install
`
$ tar -zxf git-1.7.2.2.tar.gz
$ cd git-1.7.2.2
$ make prefix=/usr/local all
$ sudo make prefix=/usr/local install
`
## 4>get git via git
`
$ git clone git://git.kernel.org/pub/scm/git/git.git
`

# INSTALLING ON LINUX
### debian :
``
apt-get install git
``

### fedora :
``
yum install git
``
