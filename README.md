gentoo-hardened-xen
===================

configurations and other things related to running gentoo on xenserver.

the files contained herein are for running gentoo on a xen hypervisor, this has only been tested with xenserver, but should work on normal xen since the drivers are the same.

the kernel configuration contains only the drivers needed for running on xen, and not much else. there are pax related items disabled due to the conflicts with xen that would prevent booting.
