# Doing a Dispatch Shift

## Starting Your Shift
When you start your shift:

- Open up the [Expert Chat](https://learn.co/expert-chat) window
- Write `qbot in dispatch` in the `#technical-coaches` Slack channel
- Greet the other TCs on shift and see how the day has been going 

If this is the first shift of the day, the Technical Coaches who are on shift will have to decide between them who the dispatcher is. You will then `qbot in dispatch` in the `#technical-coaches` channel. The dispatcher is in charge of handing this role off to another TC sometime during their shift or at the end of their shift. 

## During Your Shift
The Technical Coach on dispatch greets all incoming chats and gets some preliminary information from the students. 

If the issue is a simple question with a discrete answer (e.g. "What's the difference between `#find` and `#detect` in ruby?"), you can answer it in the chat and/or direct them to a resource (e.g. "They're the same thing :) As you can see here: https://ruby-doc.org/core-2.2.3/Enumerable.html#method-i-detect they're used interchangeably."). Similarly, if the issue is solved by something in the [Help Center](http://help.learn.co/), link them to the doc before linking the student to a coach.

If it's clear that the student will need more than a link and a few short answers, set them up to pair program by saying something like: `"Would you like to pair program with a technical coach for 20 minutes?"`

When you ask the student if they want to pair program, **make sure to add pair program (and not screen share) with a Technical Coach. This will help them get comfortable with the idea of pair programming with another developer**. This also lets them know that TCs are alloted 20 minutes per pairing.

If the student agrees, copy the question link by clicking on the clipboard:

![question link](https://s3.amazonaws.com/learn-experts/expert-chat-clipboard.png)

Paste the link into the `#technical-coaches` channel to queue up the question for the next available TC on sync support.

You will also want to periodically track the pairing that other TCs are currently on. Typing `qbot who is on?` will yield information about which TC's are active with which students and how long they've been pair programming. At 15-18 minutes, you can type something like: "`@username 15 minute mark!`", which will send a notification alerting the TC they only have 5 minutes left. If they are past the 18 minute mark, type something like: "`@username 18 minutes! Please wrap up!`". We try to be fair to our students and give them all the same amount of attention.

If you're fielding chats and see another student that is genuinely being helpful to the original poster, that's awesome. Encourage them and let everyone know you're there to help if they have problems/issues/questions.

If you notice there are a lot of questions on AAQ, and the sync's are free, make sure to keep them queue'd up. You can check the queue by typing `qbot q`. That way each student gets proper one on one support.

If you queue a student but they have already figured out the issue, you can type `qbot resolve <question_id>`. You can find the question id by typing `qbot q` - this will yield something like `https://learn.co//lessons/25366?batch_id=306&track_id=23144/&question_id=96994`. In this example you could type `qbot resolve 96994` in order to resolve the question and remove it from queue.

**Do not resolve questions for students on AAQ. Only resolve questions where the last respond time by the original poster is more than 10 hours old.**

## Ending Your Shift
At 5 minutes before your shift ends, make sure to type `@here dispatch available in 5 minutes` in order to let other TCs know that dispatch will be available. It is your responsibility to make sure the dispatch role is filled when you your shift ends. If no one volunteers, feel free to pick someone - you can use a [random name selector](https://www.miniwebtool.com/random-name-picker/) to do this. 

Once your shift is over, type `qbot out` to end your shift.

## Resources

* [Dispatch Cheat Sheet](https://github.com/flatiron-labs/technical-coach-resources/blob/master/dispatch-cheatsheet.md)
* [Qbot Commands](https://github.com/flatiron-labs/online-ed-ops/blob/master/technical-coach-team/role-technical-coach/lib/qbot.md) 
