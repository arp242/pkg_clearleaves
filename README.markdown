For FreeBSD there's a tool called [`pkg_cutleaves`][cl], which is a *very* handy
tool to quickly remove unneeded packages.

None of the Linux systems that I've worked with (Arch, Ubuntu, CentOS) come with
such a tool, nor have I been able to find one that works as well as
`pkg_cutleaves`.

So here it is! It's cross-platform, and should work on FreeBSD and `pacman`
systems (eg. Arch Linux).

This only implements the visual mode, and not the interactive mode, as I find
that to be much more useful. Note that the flags are *not* compatible with
`pkg_cutleaves`.

Please email me at [martin@arp242.net][mail] if your system isn't supported, if you
provide some example outputs then I'm sure we can fix that ;-)

[cl]: http://www.freshports.org/ports-mgmt/pkg_cutleaves/
[mail]: mailto:martin@arp242.net
