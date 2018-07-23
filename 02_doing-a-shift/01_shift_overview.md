# Shift Overview 
On a standard shift, one coach acts as dispatcher and fields all incoming questions. They chat directly with students who have simple questions and queue up students that need more support for 20 minutes screenshares with the other TC's. The one on one support model is based around giving each student a small bit of your time, but all of your attention.

## Shift Roles
On a standard shift, there are two roles: **dispatch** and **sync**. We'll cover these roles in greater depth in subsequent sections.

### Dispatch
The Dispatcher fields all incoming chats from students and gets some preliminiary information from them. There is only one Dispatcher per shift. 

If the issue is a simple question with a discrete answer (e.g. "What's the difference between #find and #detect in ruby?"), you can answer it in the chat and/or direct them to a resource (e.g. "They're the same thing :) As you can see here: https://ruby-doc.org/core-2.2.3/Enumerable.html#method-i-detect they're used interchangeably."). 

If it's clear that the student will need more than a link and a few short answers, set them up to pair program with another TC who's in the Sync role. 

### Sync
If you're on Sync during a shift, you'll be screensharing with students. Depending on their issue, you may be doing anything from debugging a simple syntax error, to troubleshooting an environment issue, to teaching a concept to a struggling student. We limit our screenshares to 20 minutes - you may not always be able to solve the error within this time limit, but that's okay - do the best you can.

## Slack Channels - Flatiron Staff
While working on a shift, you will likely find yourself accessing a number of different Slack channels in the Flatiron Staff team. Below is a brief overview of what some of these channels are. For more in depth information, check out the resources at the end of this lesson.

### #technical-coaches
The `#technical-coaches` channel is used for doing your shift and all shift related content. It's also used to greet your peers and a little chat. Please try not to flood technical coaches with chat however, if it's an in depth discussion, you can always do a group DM.

### #labs-escalation
The `#labs-escalation` channel is read-only - any time a Jira ticket is filed by a TC, a message will be posted to this channel. This channel is not to be used as a chat, but can be used to post necessary escalations by TCs (e.g. AAQ is down).

### #tc-updates
The `#tc-updates` channel is used by the Technical Coach Leads, Technical Coach Manager, or other Departments to keep Technical Coaches updated on various issues. Other departments such as engineering may use this channel if learn.co or Github is down. This channel is not to be used as a chat or to post escalations. 

### #tc-support
The `#tc-support` channel is used for finding already answered questions as well as asking your own questions. You will want to first do a search for a question you might have. If there are no questions already answered in that topic, open your own thread with the question. Technical Coaches will then reply to any question you may have as threaded replies.

### #virtual-box
The `#virtual-box` channel contains lots of useful information for VirtualBox, software that allows students to run a virtual machine on their computer if they're not using OSX. This channel has links to available resources, videos and the Github docs with fixes to the most common known issues.

## Qbot
`Qbot` is the helpful Slack bot that manages who's on shift and the questions queued for screen share. We reference some of these commands in this curriculum track. You'll be using these commands frequently on shift, so please [check out the full documentation for qbot here](https://github.com/flatiron-labs/online-ed-ops/blob/master/technical-coach-team/role-technical-coach/lib/qbot.md).

## Categories of Questions
You'll see three categories of questions on AAQ - **Requires Action**, **Active Questions** and **Inactive Questions**:

- **Requires Action** is any new question or any question where the student has responded and has been waiting > 15 mins for a TC response. These are top priority and we should keep it empty. If we see something in requires action, we want to move it out of there as fast as we can.
- **Active Questions** contains questions where a coach and a student are actively chatting.
- **Inactive Questions** are questions where a student hasn't responded to a coach for at least 15 minutes, so you can ignore them until the student replies. When they reply, the question will be moved back into the Active Questions category. 

## Breaks
While on a shift, you are permitted one 10 minute break. You can take this break in the middle of your shift as long as no other TC is already on break. You can't take your 10 at the beginning of a shift (and show up late) or take a break at the end (and leave early). There shouldn't be more than one TC on break at a time. Best practice is to clear it with dispatch before you take your break. When you're ready to break, `qbot out` so no questions are assigned to you. When you're break is done, message `qbot in <role>` in Slack. 

If you're working a double shift, you are permitted one 30 minute break and one 10 minute break. You can't take these breaks back to back (so no 40 minutes breaks). Same rules as regular breaks apply: Take them in the middle of your shift and if no other TCs are already on break. If you're breaking for 30 minutes, try to wait until the chat is quiet and not extra busy, if possible - the other TCs on shift will thank you for it!


## Resources
* [Qbot Commands](https://github.com/flatiron-labs/online-ed-ops/blob/master/technical-coach-team/role-technical-coach/lib/qbot.md) 
* [AAQ](https://learn.co/expert-chat)
* [Chrome Extension for tracking questions](https://chrome.google.com/webstore/detail/le3/hjjhpafjpkkjbdchnaeikofponobhngc)
* [#technical-coaches channel information](https://github.com/flatiron-labs/technical-coach-resources/blob/master/tc_channels/technical_coaches_channel.md)
* [#labs-escalation channel information]
* [#tc-updates channel information](https://github.com/flatiron-labs/technical-coach-resources/blob/master/tc_channels/technical_updates_channel.md)
* [#tc-support channel information](https://github.com/flatiron-labs/technical-coach-resources/blob/master/tc_channels/technical_support_channel.md)
* [Virtual Box Info](https://github.com/flatiron-labs/technical-coach-resources/blob/master/virtual-box-setup-errors-and-resources.md)
