gitolite-web-hook
=================

github like web hook, which is posting commit/push information as json (also see https://developer.github.com/webhooks/creating/)

The URL to which the commit messages are being posted, needs to be configured inside the script

local/hooks/repo-specific/wyona-continuous-notify-push

(see the parameter URL)

Inside conf/gitolite.conf please use it as follows:

repo    foor-bar-repo  
        option hook.post-receive = wyona-continuous-notify-push
