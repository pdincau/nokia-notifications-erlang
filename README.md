nokia-notifications-erlang
==========================

This software provides an Erlang client for  [`Nokia Notifications`](http://developer.nokia.com/nokia-x/nokia-apis/nokia-notifications "Nokia Notifications").

Since the protocol used is close to GCM you can customize [`gcm-erlang`](https://github.com/pdincau/gcm-erlang "gcm-erlang"). You just need to change the endpoint in `gcm_api.erl`.

This is just a fix, since Nokia Notifications does not support all of GCM features. Therefore if you are interested in getting a working library only for Nokia Notifications please open an issue in this repository.
