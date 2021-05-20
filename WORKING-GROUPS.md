# Creating an Ansible Working Group

## What are Working Groups


Working Groups are a way for Ansible community members to self-organize around particular topics of interest.

The basic components of a working group:
* A group name and charter (why the group exists);
* A registered IRC channel on [irc.libera.chat](https://libera.chat/) (will usually be #ansible-groupname);
* A group of users (at least two!) who will be driving the agenda of the working group;
* Dedicated wiki space.

The basic responsibilities of a working group:
* Be responsive on your IRC channel;
* Report semi-regularly on the cool stuff that your working group is working on;
* Keep your wiki space clean!

## Requesting a Working Group

Anyone can request to start a Working Group, for any reason. 

Cut and paste the following text into an [Community Issue](https://github.com/ansible/community/issues/new), and replace the examples in brackets
with your own working group info:

```
WORKING GROUP NAME:    [ Example: unicorn   ]

WORKING GROUP PURPOSE:
[ Example: This working group is to review  ]
[ all Unicorn-related modules               ]
[                                           ]
(keep it short and sweet)

AT LEAST TWO INITIAL WORKING GROUP MEMBERS:
[ IRC: gregdek / GitHub: @gregdek           ]
[ IRC: rbergeron / GitHub: @robynbergeron   ]
[                                           ]
(provide the IRC nicks AND GitHub IDs of your working group members, one name per line please)
```



## Process for Ansible Staff

We will ask you a few more questions if anything is unclear via the GitHub issue created above.

Once we have enough information, we will set up the following infrastructure:
* An IRC channel on libera.chat named "#ansible-yourgroupname", properly registered and op'd;
  * `*!*@ansible/owner/*    +AORefiorstv`
  * `*!*@ansible/staff/*    +Oo`
  * Group Contact set - via Jimi-C
* github.com/community
  * Wiki new page and link from [1](https://github.com/ansible/community/wiki/_Sidebar/_edit) & [2](https://github.com/ansible/community/wiki/Home/_edit) and 
   A label in the issue tracker to identify issues/PRs for your working group;
* a/a label - update BotMeta
  * Search for `linode -label:linode` (and other related terms) to find other issies & PRs where the label needs adding
  * Add other `keywords:` to BOTMETA
  * Ensure set for module, module_utils, docs_fragments, integration tests, unit tests
* [Ansibullbot](https://github.com/ansible/ansibullbot/blob/master/ansibullbot/triagers/plugins/community_workgroups.py) to know about new Working Group
* Publicise
  * Internal Email & Slack
  * IRC: `#ansible-devel`  `#ansible` 
  * [Changes impacting Contributors](https://github.com/ansible/community/issues/346)
  * [The Bullhorn](https://github.com/ansible/community/issues/546)
  * Google Groups: `ansible-project` & `ansible-devel`

## Help!

If you get stuck or want to know more join us in `#ansible-community` on [irc.libera.chat](https://libera.chat/)
