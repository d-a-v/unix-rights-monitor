unix-rights-monitor
===================

On some directories shared by people, automatically set the
owner/group/mode of created dir/files in background.
Can be started from user's .login/.profile .
Based on linux kernel inotify.

Example: 
./linux-rights-monitor -chgrp project -fchmod g+w -dchmod g+wx /net/server/project/work1 /net/server/project/work2
