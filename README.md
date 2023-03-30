# Vectara protobufs
[Vectara](https://vectara.com) implements a gRPC API (as well as REST APIs) for all
of its core services.  This repository holds the official protobuf definitions for
those gRPC APIs.

These gRPC APIs generally provide for slightly lower latencies and much stronger
types than what REST services can generally provide due to the nature of gRPC (though
Vectara is indifferent if you prefer to use REST because you find it more familiar).

If you'd like to learn more about using Vectara through its APIs, have a look at
[Vectara's online documentation](https://docs.vectara.com/docs/)

If you'd like to see code samples of using these protobuf files in a variety of
programming languages, have a look at https://github.com/vectara/getting-started

# Feedback on this repo and Vectara's APIs
These protobufs in this repository are automatically generated from Vectara and is
read-only for the general public.  If you have feedback on Vectara or its APIs,
please [let us know in our forums](https://discuss.vectara.com/)!
