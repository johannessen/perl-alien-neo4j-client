# NAME

Neo4j::Client - Build and use the libneo4j-client library

# SYNOPSIS

    use ExtUtils::MakeMaker;
    use Neo4j::Client;
    
    WriteMakefile(
      LIBS => Neo4j::Client->libs,
      CCFLAGS => Neo4j::Client->cflags,
      ...
    );

# DESCRIPTION

Chris Leishman's
[libneo4j-client](https://github.com/cleishm/libneo4j-client) is a C
library for communication with a Neo4j (&lt;v4.0) server via the Bolt
protocol. 

Installing this module will attempt to build the API portion of the
library on your machine. `libneo4j-client`'s interactive shell and 
documentation are not built.

Thanks to the miracle of [Alien::Build](https://metacpan.org/pod/Alien::Build), the library should always
contain OpenSSL support. 

# SEE ALSO

[Neo4j::Bolt](/lib/Neo4j/Bolt.md).

# AUTHOR

    Mark A. Jensen < majensen -at- cpan -dot- org >
    CPAN: MAJENSEN

# ACKNOWLEDGMENT

Thanks [ETJ](https://metacpan.org/author/ETJ) (a.k.a mohawk) for beaming me aboard.

# LICENSE

This packaging software is Copyright (c) 2020 by Mark A. Jensen.

This is free software, licensed under:

    The Apache License, Version 2.0, January 2004

The [libneo4j-client](https://github.com/clieshm/libneo4j-client) software 
is Copyright (c) by Chris Leishman. 

It is free software, licensed under:

    The Apache License, Version 2.0, January 2004
