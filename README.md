# EVolocityProtobuf
EVolocity Protobuf common files

Include `evolocity.pb.h` & `evolocity.pb.c` in C/C++ projects that need to use protobuf.

Protobuf packets are described in `evolocity.proto`.

To regenerate C/C++ source, run `pipenv run python ./nanopb-win/generator/nanopb_generator.py evolocity.proto`.
You will need Python and PipEnv.
