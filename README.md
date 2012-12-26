emqtt
=====

erlang mqtt broker.

requires
========

erlang R15B+ 

git client

build
=======

make

release
=======

make generate

deloy
=====

cp -R rel/emqtt $INSTALL_DIR

start
======

cd $INSTALL_DRI/emqtt

./bin/emqtt console

or

./bin/emqtt start

status
======

./bin/emqtt_ctl status

stop
====

./bin/emqtt stop

logs
====

log/*

design
=====

https://github.com/emqtt/emqtt/wiki