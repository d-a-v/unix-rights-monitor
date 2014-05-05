unix-rights-monitor
===================

On some directories shared by people, automatically set the
owner/group/mode of created files in background.
Can be started from user's .login/.profile.based on linux
kernel inotify.

Example: 
$1 -chgrp project -chmod g+w /net/server/project/work1 /net/server/project/work2
