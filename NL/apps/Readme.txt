Tcl/Tk 8.3 for Windows, Binary Distribution

RCS: @(#) $Id: README.binary,v 1.16 2000/02/08 10:07:05 hobbs Exp $ 

1. Introduction
--------------- 

This directory contains the binary distribution of Tcl/Tk 8.3.0 for
Windows.  It was compiled with Microsoft Visual C++ 5.0 using Win32
API, so that it will run under Windows NT, 95, 98 and 2000.

Tcl provides a powerful platform for creating integration applications
that tie together diverse applications, protocols, devices, and
frameworks.  When paired with the Tk toolkit, Tcl provides the fastest
and most powerful way to create GUI applications that run on PCs, Unix,
and the Macintosh.  Tcl can also be used for a variety of web-related
tasks and for creating powerful command languages for applications.

Tcl is maintained, enhanced, and distributed freely as a service to the
Tcl community by Scriptics Corporation.

2. Documentation
----------------

The official home for Tcl and Tk on the Web is at:
	http://www.scriptics.com

The home page for the Tcl/Tk 8.3 release is
	http://www.scriptics.com/software/8.3.html

Information about new features in Tcl/Tk 8.3 can be found at
	http://www.scriptics.com/software/whatsnew83.html

Detailed release notes can be found at
	http://www.scriptics.com/software/relnotes/tcl8.3.0

Information about Tcl itself can be found at
	http://www.scriptics.com/scripting/

There are many Tcl books on the market.  Most are listed at
	http://www.scriptics.com/resource/doc/books/

There are notes about compiling Tcl at
	http://www.scriptics.com/support/howto/compile.html

3. Installation
---------------

The binary release is distributed as a self-extracting archive called
tcl83.exe.  The setup program which will prompt you for an
installation directory.  It will create the installation heirarchy
under the specified directory, and install a wish application icon
under the program manager group of your choice.

We are no longer supporting use of Tcl with 16-bit versions of
Windows.  Microsoft has completely dropped support of the Win32s
subsystem.

4. Linking against the binary release
--------------------------------------

In order to link your applications against the .dll files shipped with
this release, you will need to use the appropriate .lib file for your
compiler.  In the lib directory of the installation directory, there
are library files for the Microsoft Visual C++ compiler:

	tcl83.lib
	tk83.lib

5. Building dynamically loadable extensions
--------------------------------------------

Please refer to the example dynamically loadable extension provided on
our ftp site:

	ftp://ftp.scriptics.com/pub/tcl/misc/example.zip

This archive contains a template that you can use for building
extensions that will be loadable on Unix, Windows, and Macintosh
systems.

6. Reporting Bugs
-----------------
If you have comments or bug reports for the Windows version of Tcl,
please use our on-line bug form at:

http://www.scriptics.com/support/bugForm.html

or post them to the newsgroup comp.lang.tcl.

7. Tcl newsgroup
-----------------

There is a network news group "comp.lang.tcl" intended for the exchange
of information about Tcl, Tk, and related applications.  Feel free to use
the newsgroup both for general information questions and for bug reports.
We read the newsgroup and will attempt to fix bugs and problems reported
to it.

When using comp.lang.tcl, please be sure that your e-mail return address
is correctly set in your postings.  This allows people to respond directly
to you, rather than the entire newsgroup, for answers that are not of
general interest.  A bad e-mail return address may prevent you from
getting answers to your questions.  You may have to reconfigure your news
reading software to ensure that it is supplying valid e-mail addresses.

8. Tcl contributed archive
--------------------------

Many people have created exciting packages and applications based on Tcl
and/or Tk and made them freely available to the Tcl community.  An archive
of these contributions is kept on the machine ftp.neosoft.com.  You
can access the archive using anonymous FTP;  the Tcl contributed archive is
in the directory "/pub/tcl".  The archive also contains several FAQ
("frequently asked questions") documents that provide solutions to problems
that are commonly encountered by TCL newcomers.

9. Tcl Resource Center
----------------------
Visit http://www.scritics.com/resource/ to see an annotated index of
many Tcl resources available on the World Wide Web.  This includes
papers, books, and FAQs, as well as extensions, applications, binary
releases, and patches.  You can contribute patches by sending them
to <patches@scriptics.com>.  You can also recommend more URLs for the
resource center using the forms labeled "Add a Resource".

10. Mailing lists
----------------

A couple of mailing lists have been set up to discuss Macintosh or
Windows related Tcl issues.  In order to use these Mailing Lists you
must have access to the internet.  To subscribe send a message to:
	
	wintcl-request@tclconsortium.org
	mactcl-request@tclconsortium.org
	
In the body of the message (the subject will be ignored) put:
	
	subscribe mactcl Joe Blow
	
Replacing Joe Blow with your real name, of course.  (Use wintcl
instead of mactcl if you're interested in the Windows list.)  If you
would just like to receive more information about the list without
subscribing put the line:

	information mactcl
	
in the body instead (or wintcl).


