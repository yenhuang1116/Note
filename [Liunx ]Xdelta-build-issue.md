# Xdelta-build-issue

>[參考連結](https://github.com/jmacd/xdelta/issues/235#issuecomment-388802811)

Download the source from the ubuntu package and compile that instead... (Hey it works...)

https://launchpad.net/ubuntu/+source/xdelta3/3.0.11-dfsg-1ubuntu1

Do the following:

wget https://launchpad.net/ubuntu/+archive/primary/+sourcefiles/xdelta3/3.0.11-dfsg-1ubuntu1/xdelta3_3.0.11-dfsg.orig.tar.xz

tar -xf xdelta3_3.0.11-dfsg.orig.tar.xz

cd xdelta3-3.0.11-dfsg

./configure

make
