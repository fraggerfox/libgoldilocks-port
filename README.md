libgoldilocks-port
==================

FreeBSD Ports script for libgoldilocks.

You can find libgoldilocks [here][1]

NOTE: This port is not yet available in the FreeBSD Ports tree.
NOTE: This library does not have release yet.

Installation
------------

Copy `security/libgoldilocks` folder to `/usr/ports` directory.

NOTE: If your ports directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/ports/security/libgoldilocks`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

Credits
-------

* The libgoldilocks is developed and maintained by the [OTRv4 Team][3]
* Thanks to `@ppaeps` for a machine to do and test the port development and
  testing out / fixing the port.
* This work has been partially sponsored by [CAD][4]

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/otrv4/libgoldilocks
[2]: https://github.com/otrv4/libgoldilocks#building-the-library
[3]: https://github.com/orgs/otrv4/people
[4]: https://autonomia.digital/
