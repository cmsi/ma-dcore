# ma-dcore

## How to prepare source files for dcore package

        VERSION=1.0.0
        cd $HOME/vagrant/data/src
        wget -O dcore-$VERSION.tar.gz https://github.com/issp-center-dev/DCore/archive/v$VERSION.tar.gz
        tar zxvf dcore-$VERSION.tar.gz
        mv -f DCore-$VERSION dcore_$VERSION
        tar zcvf dcore_$VERSION.orig.tar.gz dcore_$VERSION
        rm -rf dcore-$VERSION.tar.gz dcore_$VERSION
