# Submitting a Jira Ticket

## Pre-Escalation Checklist

As reporting an issues is a heavy load on our development team there are steps that must be taken before reporting _any_ issue:

- Make sure you or the student (whoever is experiencing the issue) has tried fully refreshing the page
- Browse or search [the technical coaches resources repo]() and the [help center](http://help.learn.co/) using keywords or error messages to see if you can find a solution 
- If the student is having an issue in the Learn IDE, you should be able to re-create this same issue **in your own Learn IDE**.
- Search the `#tc_support` channel for any possible solutions
- Do an `@here` in the `#technical-coaches` channel to see if any of the other technical coaches can help
- Do a quick Google / StackOverflow search for any possible solutions

If you are unable to resolve the issue using the above methods, proceed to report the issue through Jira.

### How to report an issue through Jira
If you are running into an issue that is beyond your ability, hit the Log Bug Report button in /expert-chat.

![log button](https://s3.amazonaws.com/learn-experts/jira-log-bug-report.png "log button")

This will bring you to Jira, where you need to press the Create button at the top of the screen.

![create issue](https://s3.amazonaws.com/learn-experts/jira-create-issue.png "Create Issue")

This will bring up a modal for you to create a ticket based on issue type.

Select the appropriate issue type and fill in all required and optional fields.

![issue modal](https://s3.amazonaws.com/learn-experts/jira-issue-modal.png "Issue Modal")

When creating your ticket make sure to include:

- Student, lab, and environment info
- All steps taken to try and resolve the error
- What you saw and what you expected to see
- Steps to re-create the error (it's alright if it's not possible to re-create the error on your machine, but at least include the steps needed to create the error on the student's machine)
- Screenshots if available

**Example**
```
Full Name: Michael Jackson
Github Username: HeeHee
Lab: Music CLI lesson

OS: Sierra
Environment: Learn IDE V3

Issue: Test and PR light won't turn green after passing test and doing learn submit

Thing's we've tried:
- Refresh the page (after everything we tried)
- Checked connection to learn with learnwhoami
- Checked internet connection 30Mbs D / 10MBS U
- Deleted forked repo and re forked, ran learn and learn submit
- Deleted local copy and re-cloned, ran learn and learn submit

Attached is some errors in the console of the ide while running learn and learn submit
```

**Note**: Do not just rely on the dev team reading through the chat transcript. Please provide a summary as best you can so they don't have to dig through the chat. Once you've filled in all the fields, you'll need to set a priority level.

### Priority Level

There are a few different priority levels and it's important to pick the right one. The table below gives a quick overview of issues priorities and their definitions.

| Priority | Definition | 
| -------- | ---------- |
| Blocker | Issues that prevent paid users from learning, or sitewide issues that affect all users. For example: a paid user's IDE not working or they can't access their track or billing. Or, `/expert-chat` is broken, or learn.co is down. **Use with caution**. |
| High | Issues that prevent unpaid users from learning, or a paid student has an issue that is causing a poor experience. For example: a paid user's lights on learn.co aren't or is having chat issues; an free user can't access a free track or get their IDE to work.
| Medium | An issue that needs to be addressed and may be causing a poor experience but does not need to be fixed for a few business days. For example, a paid user has Slack invitation issues, or can't switch their blog type; a free user's track lights won't flip but they can proceed. 
| Low |An issue that would be nice to fix, but can be addressed down the road during a clean up week. For example, visual quirks, feature requests or improvements; free user has has a problem with slack or their progress data is incorrect.

**Raising a blocking issue will alert the entire Flatiron staff. Use ONLY for critical issues.**

[Use this spreadsheet to determine which priority level you should use](https://docs.google.com/a/flatironschool.com/spreadsheets/d/1_yr-CsT0hIfSEcz9vv9yjkRGWQLeKmG40SNjywphoOc/edit?usp=sharing)

**Note** If this is a Blocker level issue, there are that will need to be done before submitting. Also, you will need to know if the student is a paying student or not to properly determine the priority level. **If the student can move forward (go to the next lesson for now), then this is not a blocking issue.**

## Resources

- [Escalation Guide](https://github.com/flatiron-labs/learn-support/blob/master/escalation.md)