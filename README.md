unix-rights-monitor
===================

On some directories shared by people, automatically set the
owner/group/mode of created/modified files in background,
started from user's .login/.profile, based on linux kernel
inotify.

example: 
./linux-rights-monitor -chgrp project -chmod g+w /net/server/project/work1 /net/server/project/work2

