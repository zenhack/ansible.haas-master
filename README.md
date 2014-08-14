Note: this is unmaintained; the current development focus is on our
[puppet module][3].

This repository contains an [ansible][1] role for managing a HaaS
master, i.e. a machine which runs the [HaaS][2].

It is at present very incomplete, and only supports CentOS. Other
rpm-based distributions may work, but have not been tested.

Note that right now this is geared towards development; the HaaS isn't
suitable for production use yet anyway. As such, it includes a few
extras like git.

[1]: http://www.ansible.com
[2]: https://github.com/CCI-MOC/haas
[3]: https://github.com/CCI-MOC/puppet-haas
