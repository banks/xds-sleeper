# Useless xDS Server

This is an xDS server that Envoy can use to discover precisely nothing.

It never delivers any config. It's only purpose is to attempt a really simple
reproduction of an issue seen in integration tests against a real xDS server
(Consul) which _seemed_ to indicate a bug in Envoy. This server helps prove
that's not the case.