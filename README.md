$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/bur1aku/tema-2.git'

user@WINDOWS-VD1FRAU MINGW64 ~/Desktop/tema 2 (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@WINDOWS-VD1FRAU MINGW64 ~/Desktop/tema 2 (master)
$ git push --set-upstream origin master
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 388 bytes | 388.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/bur1aku/tema-2.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

user@WINDOWS-VD1FRAU MINGW64 ~/Desktop/tema 2 (master)
$
