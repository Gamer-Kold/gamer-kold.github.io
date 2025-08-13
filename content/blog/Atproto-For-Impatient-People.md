+++
title = 'Atproto For Impatient People'
date = 2025-07-25T09:17:41+05:00
draft = true
blog_tags = []
+++

[Bluesky](https://bsky.app) is an emerging twitter-like microblogging site that has
been increasing in prominence as of late. The actual network itself is rather uninteresting,
rather, the most interesting thing about it is the protocol it's built on.

The Authenticated Transfer Protocol (oft abbreviated as simply atproto) is a protocol for 
decentralized social media, it lets you post and reply and interact with or without the intervention
of Bluesky PBC (more on what this practically looks like later).

Here's a bird's eye view. You, as a user, pick a place to store your data. You can imagine as sort
of a data warehouse. This is your _PDS_ or Personal Data Server.

```
  _________________________
 /                         \
|---------------------------|
|                           | <---- Your data
|            PDS            |       lives here
|                           |
|             ,             |
|____________| |____________|
```

Some warehouses have a lot of users (like the ones that belong to Bluesky PBC), some have only one.
The point to remember is to participate, you do pick one, even if you don't know it. Then, when you
make a post, the Bluesky app _sends_ it to your data warehouse.

```
                                      ,
                                     / \
                                    /   \
                                  ---------  I'd like to make a post
                                  (,  o o| /
                                    \___/
                         
                                      |
                                      |
                                      |
                                      V
                                 ,'',   ,'',
                                 |   \,/   |   Oh ok i'll tell the PDS
                                  \       /  < to store it 
                                  /  /'\  \
                                 ',,'   ',,'
                              Your Bluesky Client
                                      |
                                      |
                                      |
                                      |
                                      V 
                          _________________________
                         /                         \
                        |---------------------------|
                        |                           |
                        |            PDS            |
                        |                           |
                        |             ,             |
                        |____________| |____________|
```


