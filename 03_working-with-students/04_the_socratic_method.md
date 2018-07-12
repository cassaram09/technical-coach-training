# The Socratic Method

![Socrates](https://s3.amazonaws.com/learn-experts/socrates-atenas-9352.jpg)

> “I cannot teach anybody anything. I can only make them think.”
> ― Socrates

You've probably heard the phrase [Socratic Method](http://www.criticalthinking.org/pages/socratic-teaching/606) but why do we care so much about it? The focus of the Socratic Method is on asking questions and not on giving answers. By asking specific, guided questions we get students to think critically about their responses, connect pieces of information together, and, in the process, learn how to learn.

**Video Example** [Learning with a student using the Socratic Method](https://youtu.be/MURwX6jUlRk)

Now that you know what the student’s bug is, help them figure out what the problem is without giving them the answer right away. Use questions that will get them to explain their process and in this way, they may realize themselves what their mistake was.
  - As a rule of thumb, in the text chats that you have with a student, they should be “talking” at least 50% of the time. In pair programming, they should be talking about 50% of the time.

**Video Example** [Technical Coach asking poking questions to student](https://youtu.be/aMZFyDrT0S4)

### Know where to start asking questions

* Do they understand the error message? What is it saying? What line(s) did the occur on (in both their code and the test file)? Make them explain the error message to you.
* The student got an error message, but what did they _expect_ to happen?
* If a student’s error message is tied specifically to a method then start your questions with that method (eg what are the methods inputs, outputs, etc).
* However, if the student’s error message is related to issues outside of the specific method and there might be larger conceptual issues, you should start your questioning with those concepts (eg iterating through an array).

### How to ask questions

Use the same approach you took yourself when you were debugging the student’s code.

Ask them to walk you through their code by breaking it into structured steps where they go operation by operation. If you need input data to talk through the code, direct them to whatever the test feeds in for this particular failing test.

Ask the student what the purpose of their method is, what the inputs of the method are, and what they expected to be the result.

When you get to the point of the student’s mistake, there are a few strategies you can employ to get the student to realize their own mistake:

* Ask additional questions about why they thought this was correct such as “What do you think this line returns?” **Always ask them to try out the code in IRB, pry, console, or debugger.** We want students to get into the habit of using debugging tools.
Point the student to resources or tell them the specific things in a lesson or lab that they need to re-read.
* Restate the student’s incorrect process or assumptions. Seeing it written out by someone else can give the student enough distance to see what their mistake was. “What does your_variable equal here?” and “What kind of object does method `#some_method` return?”
* Use questions instead of statements. Instead of telling them their mistake, we should probe and attempt to get them to discover it on their own.  For example, instead of saying “Your method requires two arguments,” we should ask "How many arguments does our method require? How can we find out?". This puts the onus on the student to think about the problem  and how to solve it.
* Sometimes, if a student is especially frustrated or not understanding after several questions, it’s best to tell them what their mistake is, and explain why it's incorrect. If possible, try to phrase it as a question. So, instead of saying “Your method requires two arguments,” say instead "Don’t you think the method should require two arguments?" This way, the student will have to think for, even just a few seconds about their problem.

Using the Socratic Method teaches students how to debug because it shows them what questions we ask ourselves when we solve the lab. In turn, this teaches students better debugging techniques so that they’ll have a better shot debugging their code on their own in the future.

Make sure that the student is aware that your goal as a TC is to familiarize them with the sort of questions that you ask yourself when you're solving problems on your own. Remembering the sort of questions you ask them should help them improve their debugging skills.

However, if the student’s error message is related to issues outside of the specific method and it seems there are larger conceptual issues, then you should start your questioning with those concepts. If they don't understand the questions, go into teach mode and teach the concepts. Once the student understands, switch back to the Socratic method. 