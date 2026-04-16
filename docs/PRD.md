# Product Requirements Document

## Why to Create this Project

At first a hermes can only gateway a single wechat user. That'y why I come up with a requirement to manipulate more than one hermes to form a group.

The first idea is to encapsulate my hermeses in diverse Docker containers. But later I found it not easy to comunication accross containers.

Then as my research deeps in, I found hermes can create multi profiles in its file system. The default is in `.hermes/`, and others are in `.hermes/profiles/<profile_name>/`.

Going along this, I know we can manipulate more than one hermes in a single hoster.

## Concepts Declaration

We need to make some 

I've dig into existing multi-agent collaboration projects, but they don't satisfy me.
My detailed thoughts are in [here](./CA.md).

So I want to make an open-source, easy-to-use, real-time multi-agent collaboration platform.