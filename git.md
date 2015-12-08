git pull = git fetch; git merge

use git fetch if I just want to see if I can automatically merge / can be fast-forwarded

git reset --hard   will erase any local copy changes I made and overwrite them with what's on the server

follow that reset up with a 'git pull --rebase' 

See 'git help rebase' (or other git commands) for more info
