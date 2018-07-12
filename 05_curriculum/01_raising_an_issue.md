# Raising an Issue

## learn-co-curriculum v learn-co-students

![deploys](https://s3.amazonaws.com/learn-experts/deploys.png)

When we create curriculum, we create it in the `learn-co-curriculum` Github organization. All the lessons in here are called *canonical lessons*.

When we deploy curriculum, we deploy it to a different Github organization, `learn-co-students`. This will deploy the lesson to a student’s specific batch.

So for example, here is the url of the canonical version of a lab:
https://github.com/learn-co-curriculum/my-each/

And here’s the url of the deployed version of the same lab in the Full Stack Track (batch V-000):
https://github.com/learn-co-students/my-each-v-000

**When you’re raising an issue, ALWAYS make sure that you are in the canonical lesson repository.**

## When and How to Raise an Issue

Sometimes, when a student has an issue, it's an issue with the lesson and not their code. In this case, after working with the student, **ALWAYS raise an issue on the canonical lesson repository. DO NOT tell the student to raise the issue since they will not always know how best to raise one and what to include.**

Because anyone can fix or collaborate with others to fix an issue, it’s important that you explain the issue clearly so that someone looking at it will be able to understand the problem and proposed solution without having to ask for further clarification. Now you're all set to raise an issue on the curriculum!

![raise an issue](http://i.giphy.com/xT5LMtPw9a0ijuU7zG.gif)

But first, some guides to raising a _good_ issue:

### Does Your Issue Already Exist?

Review the open issues in the canonical repository to make sure that your issue hasn’t already been reported. If the issue has, then add a comment in that issue and explain that this is still a problem. If the existing issue description isn’t clear enough, clarify it using the suggestions below.

### Guidelines for Raising an Issue

**Title**  

This is the first thing that someone will see when they’re going through an open list of all issues in the learn-co-curriculum org.

Let’s look at some bad and better versions of issue titles.

* **Bad example:** HTML tags
* **Good example:** Series of HTML closing tags rendering as text
---
* **Bad example:**  Hashes, hashes, hashesags
* **Good example:** Information on hashes that’s needed to complete this lab hasn’t yet been covered
---
* **Bad example:** Cocoa pods
* **Good example:** Instructions needed on installing cocoa pods

**Issue description**

* First, indicate which track you’re working on since an individual lesson can be in multiple tracks, and if you’re referring to content outside of this specific lesson, this will better put the issue in context.

* Give a 1-2 sentence summary of the issue. Explain what you were expecting to see or happen, and what you saw or happened instead. This can vary depending on the type of issue.

* Indicate which files, folders, and/or branches in the lesson that this issue relates to. For example, if just the Readme needs to be updated, write the filename. If both the specs and the readme need to be updated or added, then write those filenames.

**For bugs and similar issues:**

Give enough information so that someone can reproduce the issue on their end. Go step-by-step and don’t assume that you can skip steps. You can also reproduce an issue by using a failing test, including sample code or screenshots with sample code, or a  gist.

After you explain how someone can reproduce the problem, in a separate paragraph, write the solution that you would like to see. If you can include the code, this would be extra helpful. Otherwise, go into detail on what the expected outcome should be.

**For issues related to syntax, style issues,  typos, broken links, and incorrect images or videos:**

If you haven’t done so already, specify the files and the lines where the issues arose. Take a screenshot and highlight the errors.

Include a suggested solution to the problem. The more detailed your solution, the faster it will get fixed. For example, in the above example, it would be great if your proposed solution had the correct urls that the page should link to.

**For issues related to missing content that is necessary to have:**

If you haven’t done so already, specify which files or folders need to be created, or the files or folders this missing content belongs in.

If not having this missing content produces a bug or a failing test, refer to the section “For bugs and similar issues” on what to include in your issue. If the missing content prevents a student from completing a task, then explain this in detail.

Then, in a new paragraph, list and explain the information that would fix the issue. Wherever possible, include in which sections of the file this information would go, ideally though screenshots, gists, or links. If you feel the information should be in a separate lesson, indicate this and where in the track you feel it belongs.

### Using @mentions

When you raise an issue on a bit of curriculum, please make sure to @ mention the section lead (https://github.com/flatiron-labs/learn-support/blob/master/learn-instructors.md#sections) in charge of that curriculum as well as cc @AnnJohn and @ruthmesfun .

## Resources

 - [Raising an Issue in the Reference Guide](https://github.com/flatiron-labs/learn-support/blob/master/how-to-raise-an-issue.md)
 