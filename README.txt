            -------------------------------------------------
            csshX - Cluster SSH tool for Mac OS X Termial.app
            -------------------------------------------------
            Copyright 2011 by Gavin Brock   <gbrock@cpan.org>
            -------------------------------------------------


INSTALLATION:

As csshX is a command line tool, no special installation is needed. It may
be copied into a directory in your path, (e.g. /usr/local/bin) for your 
convenience.

The software has been tested on Mac OS X 10.5, 10.6 and 10.7 with the default
Perl installation - no additional Perl modules are required.


DOCUMENTATION:

The documentation for csshX is self contained. Please run:

    ./csshX --man

If that does not work, you can try the FAQ:

    http://code.google.com/p/csshx/wiki/FAQ

Example Usage:

```
# copy this binary to your bin folder to make it easier to use:
cp ./csshX /usr/local/bin

# create a file which has one host on each line, e.g.:
cat <<EOF > hosts
host1.servicenow.com
host2.servicenow.com
host3.servicenow.com
EOF

# use csshX with an alternative ssh command if desired and point to the hosts file you created:
csshX --hosts hosts --ssh bssh

#A "master" terminal will pop up (it's red for me) and anything typed into it will be replicated across all terminals.
```

UPDATES:

The latest version of the software is available here:

    http://code.google.com/p/csshx/

Important update information will be posted on:

    http://gavcode.wordpress.com/tag/csshX/

Information for enthusiasts will be posted on twitter:

    http://twitter.com/csshx


LICENSE:

This program is free software; you may redistribute it and/or modify it 
under the same terms as Perl itself. 

Full details can be found by running:

    perldoc perlartistic
    perldoc perlgpl


CREDITS:

Thanks to everyone for the suggestions and bug reports. That's what makes
coding fun. In addition, I would like to thank the following people for their
patches and code: Eric Lubow, mtbeedee, Mitch Silverstein, Robin Stephenson, 
Chris Yunker, Song Gao and Jean-Sebastien Morisset.
