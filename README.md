# AAAboutCAMP
Common Algorithm Mining Project web site

Throughout the global corpus of software there are many thousands of potentially useful library routines locked up in programs.  The Common Algorithm Mining Project aims to operate as a "surgical service bureau" to convert such programs into library + wrapper executable pairs, unlocking the "hidden value" without damaging the asset.

Administratively, participation is open to anybody.  I would love to see CAMPers at "summer of code" or even "hour of code" events.  People just beginning their journey as programmers and people learnign a new language can make meaningful contributions to structured maintenance work like this.  The generic plan is to fork a program, restructure it, and submit a pull request back to the origin.  But we can and will host forks indefinitely if that's the only way forward.

I envision the CAMP "organization" undertaking to make the CAMP code transformation on non-published source trees.  This idea started out as a proposal for an undergraduate programming studio course when I was at U. Tulsa and included a protocol for working on proprietary code.  But since there is no organization except me and this page at this point we're limited to things we can do in public.

I'll have more to say as we grow but the above will have to serve as the CAMP Manifesto for now.  If you would like to become a team member or suggest a program the path for now is to drop me an email, I guess: snuchia at gmail.

Stephen Nuchia
22 December 2016

Let me add a couple of examples of the kinds of "hidden value" I'm thinking of.

1) The unix make utility reads a textual representation of a dependency tree and supervises the execution of the shell command sequences based on a model of what "out of date" means for files.  The core engine could be profitably employed in other contexts if it could be abstracted from the arbitrary object bindings of the make executable.  For instance, I'd like to replace the brittle startup sequence of the Linux kernel and many other programs with a library version of the make core.

2) I've just introduced our first fork -- Microsoft's recenlty open-sourced test vector generator PICT.  Like make, the existing program is "hopelessly" tied to textual input and output formats.  I'm interested in adapting it to interface directly with automated test environments.
