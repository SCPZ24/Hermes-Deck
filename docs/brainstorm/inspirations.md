# Why to Create this Project

## Trouble

At first a hermes can only gateway a single wechat user. I need to deploy a bot for me, my mom and dad on wechat.

That'y why I come up with a requirement to manipulate more than one hermes to form a group.

The first idea is to encapsulate my hermeses in diverse Docker containers. But later I found it not easy to comunication accross containers. Moreover, hosting a set of docker containers costs a lot of resources.

Then as my research deeps in, I found hermes can create multi profiles in its file system. The default is in `.hermes/`, and others are in `.hermes/profiles/<profile_name>/`.

Going along this, I know we can manipulate more than one hermes in a single hoster.

## More Than a Control Panel

As we are making a multi-agent control panel, it can not only just a config board for different profiles.
But a whole shelf for multi-agent collaboration.

So I want to make an open-source, easy-to-use, real-time multi-agent collaboration platform.