`git pull` actually runs git fetch; git merge

use `git fetch` if I just want to see if I can automatically merge / can be fast-forwarded

`git reset --hard`   will erase any local copy changes I made and overwrite them with what's on the server

follow that reset up with a `git pull --rebase`

See `git help rebase` (or other git commands) for more info


`git reset --soft head~1` 

...contrary to `--hard`, lets say you’ve committed some changes but you want to un-commit and keep all your changes prior to `git commit`ting them.  1 = (head - 1). If I change that 1 to a 2 it will be the second to last commit so on and so forth.  Hope that makes sense
