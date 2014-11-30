gitolite-web-hook
=================

github like web hook, which is posting commit/push information as json (also see https://developer.github.com/webhooks/creating/)

Inside conf/gitolite.conf please use it as follows:

repo    foor-bar-repo  
        option hook.post-receive = wyona-continuous-notify-push
