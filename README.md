kennel
=====

An OTP application

Build
-----

    $ rebar3 compile


Configuration
-------------

Set public and private network for the user
```erlang
O = <<"5f8dddd1-d965-45ee-b662-ca29d677a312">>.
ls_org:set_metadata(O, [{[<<"fifo">>, <<"docker">>, <<"networks">>, <<"public">>], <<"fd060fd4-b5cd-4fef-911b-a5023d8b3bb4">>}]).
ls_org:set_metadata(O, [{[<<"fifo">>, <<"docker">>, <<"networks">>, <<"private">>], <<"faa25949-e8a2-446f-b01a-ddf17f058016">>}]).
```