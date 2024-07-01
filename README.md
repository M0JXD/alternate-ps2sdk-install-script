# Alternate PS2SDK Installation Script

This is forked from the 1st version of israpps' install script. 
My pull request was open for months and he never accepted. israpps has now made non-mergeable changes to his script, so these changes are stuck in limbo.

Additions made to the original script are:

Added WSL2 detection.

Made the dependency installs line by line, so if any fail the others get installed (due to my happening with libgsl23)

Added some extra libraries/installs for the dependencies:

Option for PS2ETH install.

Added exit for each option (i.e. each switch only does it's designated task, only a "pure" call installs the sdk)

Added cancel option just prior to install with dependencies install reminder.

Added suggested commands for post install.
