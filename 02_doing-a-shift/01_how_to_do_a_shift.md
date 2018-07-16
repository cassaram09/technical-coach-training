# How To Do a Shift

## Shift Types
There are two different types of shifts we are currently running - a standard shift and a chat only shift. All student questions are managed with our online chat platform, [Expert Chat](https://learn.co/expert-chat).

### Standard Shift
On a standard shift, one coach acts as dispatcher and fields all incoming questions. They chat directly with students who have simple questions and queue up students that need more support for 20 minutes screenshares with other TC's.

### Chat Only Shift
All Technical Coaches pick up questions as they come in and try and either help a few students at a time, or do pair programming when necessary. We do chat only shifts occasionally on holidays (because we don't have enough people to do one on one).

## Shift Roles
On a standard shift, there are two roles: dispatch and sync. We'll cover these shift roles more in subsequent sections.

### Dispatch
The Dispatcher fields all incoming chats from students and gets some preliminiary information from them. There is only one Dispatcher per shift. 

If the issue is a simple question with a discrete answer (e.g. "What's the difference between #find and #detect in ruby?"), feel free to answer it in the chat and/or direct them to a resource (e.g. "They're the same thing :) As you can see here: https://ruby-doc.org/core-2.2.3/Enumerable.html#method-i-detect they're used interchangeably."). 

If it's clear that the student will need more than a link and a few short answers, set them up to pair program with another TC who's in the Sync role. 

### Sync
If you're on Sync during a shift, you'll be screensharing with students. Depending on their issue, you may be doing anything from debugging a simple syntax error, to troubleshooting an environment issue, to teaching a concept to a struggling student. We limit our screenshares to 20 minutes - you may not always be able to solve the error within this time limit, but do the best you can.

## Slack - Flatiron Staff
When on shift, you'll find yourself referencing a number of Slack channels: 

- **technical-coaches**: This channel is used for managing the shift via `qbot` and where we can ask questions and chat as a group. Use this channel in lieu of direct messages so we have a good sense of community and we can all learn from one another’s questions and answers.

- **labs-escalation**: You should not post directly into this channel. If you ever create an issue on Jira with a level of Blocking (more on this in later sections), it will automatically get posted here and you can watch any conversation around that.

- **tc_updates**: This channel is used for viewing updates on any maintenance, bug fixes, ide updates, batch notices, etc... Do not chat in this channel as it is used only for viewing these changes.

## Qbot
`Qbot` is the helpful Slack bot that manages who's on shift and the questions queued for screen share. You'll be using these commands frequently on shift, so please check out the [full documentation for qbot here](https://github.com/flatiron-labs/online-ed-ops/blob/master/technical-coach-team/role-technical-coach/lib/qbot.md).

## Categories of Questions
You'll see there are three categories of questions - Requires Action, Active Questions and Inactive Questions:

- **Requires Action** is any new question or any question where the student has responded and has been waiting > 15 mins for a TC response. These are top priority and we should keep it empty. If we see something in requires action, we want to move it out of there as fast as we can.
- **Active Questions** is for questions where a coach and a student are actively chatting.
- **Inactive Questions** are questions where a student hasn't responded to a coach for at least 15 minutes, so you can ignore them until the student replies. When they reply, the question will be moved back into the Active Questions category. 

## Doing a Standard Shift
The one on one support model is based around giving each student a small bit of your time, but all of your attention. We accomplish this by having one Technical Coach on the shift act as dispatcher and the rest providing the one on one support.

- Go into Flatiron Staff Slack - `#technical-coaches`
- Type `qbot in <role>` to log into your shift. You can either log in as `sync` or `dispatch`. If you're just starting out, you'll do sync and as you learn, you can hop on dispatch.
- Go to the [Expert Chat](https://learn.co/expert-chat) window. It shows you all questions for the batches that we support. If a question is in expert chat, we support that batch.

## Doing a Chat Only Shift
We do the chat only shift on some holidays, if we don't have enough people to do one on one support.

- Go into Flatiron Staff Slack - `#technical-Coaches`
- Type `qbot in sync` to let people know you're on and ready for your shift
- Go to the [Expert Chat](https://learn.co/expert-chat) window. It shows you all questions for the batches that we support. If a question is in coach chat, we support that batch.
- Ask previous shift (if there was one) how things went and to post a list of threads they're in the middle of and want to hand over
- Introduce yourself on those threads and read the thread history so you're up to speed with the issue (let's not make students repeat themselves)
- Respond to every active question on every thread that isn't being helped by another member of staff. If you can, help them all. If not, let them know you're busy but will try to get back to them as quickly as you can. We get that more than 1-3 lively threads at a time is challenging - just do what you can and enjoy the process!
- An active question is one where the OP (Original Poster) has made a comment that has not yet been responded to by a member of staff.

## Breaks
While on a shift, you are permitted one 10 minute break. You can take this break in the middle of your shift as long as no other TC is already on break. You can't take your 10 at the beginning of a shift (and show up late) or take a break at the end (and leave early). There shouldn't be more than one TC on break at a time. Best practice is to clear it with dispatch before you take your break. When you're ready to break, `qbot out` so no questions are assigned to you. When you're break is done, message `qbot in <role>` in Slack. 

If you're working a double shift, you are permitted one 30 minute break and one 10 minute break. You can't take these breaks back to back (so no 40 minutes breaks). Same rules as regular breaks apply: Take them in the middle of your shift and if no other TCs are already on break. If you're breaking for 30 minutes, try to wait until the chat is quiet and not extra busy, if possible - the other TCs on shift will thank you for it!

## Ending a Shift
- Welcome the people taking over your shift (if any) in the `#technical-coaches` Slack channel.
- If there isn't a coach taking over from you, let everyone you're chatting with or have chatted with during the shift know that you're going off shift. Let them know that the next person should be on (whenever they should be on).
- Post `qbot out` into the `#technical-coaches` Slack channel within Flatiron Staff
- Optional: Log your shift hours on WorkDay (we'll cover this in a later lesson) - but definitely before the end of the week!


## Resources

* [Qbot Commands](https://github.com/flatiron-labs/online-ed-ops/blob/master/technical-coach-team/role-technical-coach/lib/qbot.md) 
* [Expert Chat](https://learn.co/expert-chat)
* [Chrome Extension for tracking questions](https://chrome.google.com/webstore/detail/le3/hjjhpafjpkkjbdchnaeikofponobhngc)
