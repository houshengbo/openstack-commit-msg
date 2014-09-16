openstack-commit-msg
====================

The commit-msg file is used to generate a change-id for a patch to to be submitted to any OpenStack
project. It is very important and located under .git/hooks/ after a successful execution of the
command "git review -s". However, it is possible that git-review commands are unable to run
successfully in Mainland China due to whatever known and unknown reasons(It seems that ssh port is
blocked for some websites), so that we need to configure gerrit in other ways. The commit-msg file is
necessary to put in an accessible place. This is why this project is created.

How to use:
Put it under .git/hooks/ within any of your OpenStack projects.
Guarantee the privilege: chmod 777 .git/hooks/commit-msg
