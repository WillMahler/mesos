# Protobuf

## Project website:

https://github.com/google/protobuf

## How To Bundle:

```
curl -L -O https://github.com/protocolbuffers/protobuf/releases/download/v<version>/protobuf-all-<version>.tar.gz
tar -xzf protobuf-all-<version>.tar.gz
cd protobuf-<version>
./autogen.sh
cd ..
tar -czf protobuf-<version>.tar.gz protobuf-<version>
```

## Bundled Version

We bundle 3.7.1 in order to take advantage of C++ move support and
additional optimizations, as well as support for allocating strings
on areanas. Also see https://issues.apache.org/jira/browse/MESOS-9755.
