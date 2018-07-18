# Submitting a Jira Ticket

If an issue needs to be escalated to the development team, we [file a support ticket through Jira](https://flatiron.atlassian.net/projects/TS?selectedItem=com.atlassian.jira.jira-projects-plugin%3Areport-page). 

## Pre-Escalation Checklist

Since reporting an issue is a heavy load on our development team, there are steps that must be taken before reporting _any_ issue:

- Make sure you or the student (whoever is experiencing the issue) has tried fully refreshing the page
- Browse or search [the technical coaches resources repo]() and the [help center](http://help.learn.co/) using keywords or error messages to see if you can find a solution 
- If the student is having an issue in the Learn IDE, you should be able to re-create this same issue **in your own Learn IDE**.
- Search the `#tc_support` channel for any possible solutions
- Do an `@here` in the `#technical-coaches` channel to see if any of the other Technical Coaches can help
- Do a quick Google / StackOverflow search for any possible solutions

If you are unable to resolve the issue using the above methods, proceed to report the issue through Jira.

## How to report an issue through Jira
If you are running into an issue that is beyond your ability, hit the `Log Bug Report` button on AAQ.

![log_issue](https://raw.githubusercontent.com/cassaram09/technical-coach-training/master/images/log_bug_report.png)

This will bring you to Jira, where you need to press the plus button in the navigation to create the issue.

![create issue](https://raw.githubusercontent.com/cassaram09/technical-coach-training/master/images/create_issue.png)

This will bring up a modal for you to create a ticket based on issue type.

Select the appropriate issue type and fill in all required and optional fields.

![issue modal](https://raw.githubusercontent.com/cassaram09/technical-coach-training/master/images/create_issue_modal.png)

When creating your ticket make sure to include:

* Error category (eg IDE, Chat, UI, etc)
* Student, lab, and environment info
* All steps taken to try and resolve the error
* What you saw and what you expected to see
* Steps to re-create the error (it's alright if it's not possible to re-create the error on your machine, but at least include the steps needed to create the error on the student's machine)
* Screenshots if available

**Example**
```
Full Name: Michael Jackson
Github Username: HeeHee
Lab: Music CLI lesson

OS: OSX Sierra
Environment: Desktop Learn IDE V3

Issue: Test and PR light won't turn green after passing test and doing learn submit

Thing's we've tried:
- Refresh the page (after everything we tried)
- Checked connection to learn with learnwhoami
- Checked internet connection 30Mbs D / 10MBS U
- Deleted forked repo and re forked, ran learn and learn submit
- Deleted local copy and re-cloned, ran learn and learn submit

Attached is some errors in the console of the ide while running learn and learn submit
```

**Note**: Do not rely on the dev team reading through the chat transcript. Please provide a summary as best you can so they don't have to dig through the chat. Once you've filled in all the fields, you'll need to set a priority level.

## Priority Level

There are a few different priority levels and it's important to pick the right one. The table below gives a quick overview of issues priorities and their definitions.

| Priority | Definition | 
| -------- | ---------- |
| Blocker | Issues that prevent paid users from learning, or sitewide issues that affect all users. For example: a paid user's IDE not working or they can't access their track or billing. Or, AAQ is broken, or `learn.co` is down. **Use with caution**. |
| High | Issues that prevent unpaid users from learning, or a paid student has an issue that is causing a poor experience. For example: a paid user's lights on `learn.co` aren't or is having chat issues; a free user can't access a free track or get their IDE to work.
| Medium | An issue that needs to be addressed and may be causing a poor experience but does not need to be fixed for a few business days. For example, a paid user has Slack invitation issues, or can't switch their blog type; a free user's track lights won't flip but they can proceed. 
| Low | An issue that would be nice to fix, but can be addressed down the road during a clean up week. For example, visual quirks, feature requests or improvements; free user has has a problem with Slack or their progress data is incorrect.

**Raising a blocking issue will alert the entire Flatiron staff. Use ONLY for critical issues.**

[Use this spreadsheet to determine which priority level you should use.](https://docs.google.com/a/flatironschool.com/spreadsheets/d/1_yr-CsT0hIfSEcz9vv9yjkRGWQLeKmG40SNjywphoOc/edit?usp=sharing)

**Note: Before raising a blocking issue, you'll need to determine if the user is paying or not. Additionally, if the student can move forward (go to the next lesson for now), then it is *not* a blocking issue.**

## Resources

* [Escalation Guide](https://github.com/flatiron-labs/learn-support/blob/master/escalation.md)
* [Ticket Priority Levels](https://docs.google.com/a/flatironschool.com/spreadsheets/d/1_yr-CsT0hIfSEcz9vv9yjkRGWQLeKmG40SNjywphoOc/edit?usp=sharing)
