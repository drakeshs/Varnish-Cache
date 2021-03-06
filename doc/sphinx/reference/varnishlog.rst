.. _ref-varnishlog:

==========
varnishlog
==========

--------------------
Display Varnish logs
--------------------

:Author: Dag-Erling Smørgrav
:Author: Per Buer
:Author: Martin Blix Grydeland
:Date:   2013-05-15
:Version: 0.3
:Manual section: 1


SYNOPSIS
========

.. include:: ../include/varnishlog_synopsis.rst
varnishlog |synopsis| <query expression>

OPTIONS
=======

The following options are available:

.. include:: ../include/varnishlog_options.rst

-k num

	Only show the first num log transactions (or log records
	in -g raw mode)

	XXX: Not yet implemented

-s num

	Skip the first num log transactions (or log records if
	in -g raw mode)

	XXX: Not yet implemented

SIGNALS
=======

* SIGHUP

  Rotate the log file (see -w option)

* SIGUSR1

  Flush any outstanding transactions

SEE ALSO
========
* varnishd(1)
* varnishhist(1)
* varnishncsa(1)
* varnishstat(1)
* varnishtop(1)
* vsl(7)
* vsl-query(7)

HISTORY
=======

The varnishlog utility was developed by Poul-Henning Kamp
<phk@phk.freebsd.dk> in cooperation with Verdens Gang AS and
Varnish Software AS. This manual page was initially written by Dag-Erling
Smørgrav.


COPYRIGHT
=========

This document is licensed under the same licence as Varnish
itself. See LICENCE for details.

* Copyright (c) 2006 Verdens Gang AS
* Copyright (c) 2006-2014 Varnish Software AS
