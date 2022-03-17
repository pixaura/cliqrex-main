# Contribution Guidelines

This document outlines what you need to know before **[creating tickets](#issues-tickets-however-you-may-call-them)**
or **[creating pull requests](#pull-requests)**.

## Issues, Tickets, however you may call them

Please read the following instructions fully and follow them. You can
help the project tremendously this way: not only do you help the maintainers
to **address problems in a timely manner** but also keep it possible for them
to **fix bugs, add new and improve on existing functionality** instead of doing
nothing but ticket management.

- If you want to report a **bug**, [read "How to file a bug report" below](#how-to-file-a-bug-report)
  and *[use the provided template](#what-should-i-include-in-a-ticket)*.
  You do not need to do anything else with your ticket.
- If you want to post a **feature request** or a **documentation request**, add `[Request]`
  to your issue's title (e.g. `[Request] Awesome new feature`). A question on how to run/change/setup
  something is **not** what qualifies as a request here, use the
  [discussion board](https://github.com/pixaura/cliqrex-main/discussions) for
  such support issues.
<!-- - If you are a **developer** that wants to brainstorm a pull request or possible
  changes to the plugin system, please get in touch on the
  [community forum at community.octoprint.org](https://community.octoprint.org/c/development). -->
- If you need **support**, have a **question** or some **other reason** that
  doesn't fit any of the above categories, the issue tracker is not the right place.
  Consult the [discussion board](https://github.com/pixaura/cliqrex-main/discussions) instead.

No matter what kind of ticket you create, never mix two or more "ticket reasons"
into one ticket: One ticket per bug, request, brainstorming thread please.

> 👉 **Note**
>
> A bot is in place that monitors new tickets, automatically
> categorizes them and checks new bug reports for usage of the provided template.
> That bot will only bother you if you open a ticket that appears to be a bug (no
> `[Request]` in the title) without the complete template, and it
> will do that only to ensure that all information needed to solve the issue is
> available for the maintainers to directly start tackling that problem.

## How to file a bug report

If you encounter an issue with CliqRex, you are welcome to
[submit a bug report](https://github.com/pixaura/CliqRex/issues/new?template=bug_report.yml).

Before you do that for the first time though please take a moment to read the
following section *completely* and also follow the instructions in the
"new issue" form. Thank you! :)

### What should I do before submitting a bug report?

1. **Make sure you are at the right location**. This is the bug tracker
   of the official version of CliqRex.

   **CliqRex doesn't manage your network connection** -
   if you have any kinds of problems with that, get in touch on the
   [discussion board](https://github.com/pixaura/cliqrex-main/discussions).

2. Please make sure to **test out the current version** of CliqRex to see
   whether the problem you are encountering still exists.

   <!-- You might also want to try the current development version of OctoPrint
   (if you aren't already). Refer to the [FAQ](https://faq.octoprint.org)
   for information on how to do this. -->

3. The problem still exists? Then please **look through the
   [existing tickets](https://github.com/pixaura/cliqrex-main/issues?state=open)
   (use the [search](https://github.com/pixaura/cliqrex-main/search?q=&ref=cmdform&type=Issues))**
   to check if there already exists a report of the issue you are encountering.
   Sorting through duplicates of the same issue sometimes causes more work than
   fixing it. Take the time to filter through possible duplicates and be really
   sure that your problem definitely is a new one. Try more than one search query
   (e.g. do not only search for "loading" if you happen to run into an issue
   with your webcam, also search for "slow" etc). Do not only read the subject lines
   of tickets that look like they might be related, but also read the ticket itself!

   **Very important:** Please make absolutely sure that if you find a bug that looks like
   it is the same as your's, it actually behaves the same as your's. E.g. if someone gives steps
   to reproduce his bug that looks like your's, reproduce the bug like that if possible,
   and only add a "me too" if you actually can reproduce the same
   issue. Also **provide all information versions and different reproduction steps**
   and whatever was additionally requested over the course of the ticket
   even if you "only" add to an existing ticket. The more information available regarding a bug, the higher
   the chances of reproducing and solving it. But "me too" on an actually unrelated ticket
   makes it more difficult due to on top of having to figure out the original problem
   there's now also a [red herring](https://en.wikipedia.org/wiki/Red_herring) interfering - so please be
   very diligent here!

If in doubt about any of the above - get in touch on the [discussion board](https://github.com/pixaura/cliqrex-main/discussions)
instead of opening a ticket here. If you are actually running into a bug, we'll figure it out together
there.

### What should I include in a bug report?

First of all make sure your use **a descriptive title**. "It doesn't work"
and similar unspecific complaints are NOT descriptive titles.

**Always use the following template, even if only adding a "me too" to an
existing ticket**:

```
<!--
READ THE FOLLOWING FIRST:

This is a bug and feature tracker, please only use it to report bugs
or request features within CliqRex (not iOS, Android, network, or any unrelated issues).

Do not seek support here ("I need help with ...", "I have a
question ..."), that belongs on the discussion board at
https://github.com/pixaura/cliqrex-main/discussions, NOT here.

Mark requests with a "[Request]" prefix in the title please. For bug
reports fully fill out the bug reporting template (if you don't know
where to find some information - it's all described in the Contribution
Guidelines linked up there in the big yellow box).

When reporting a bug do NOT delete ANY lines from the template.

Make sure any bug you want to report is still present with the CURRENT
CliqRex version.

Thank you!
-->

#### What were you doing?

<!--
Please be as specific as possible here. The maintainers will need to
reproduce your issue in order to fix it and that is not possible if they
don't know what you did to get it to happen in the first place.

Ideally provide exact steps to follow in order to reproduce your problem:
-->

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

<!--
If you encountered a problem with specific files of any sorts, make sure
to also include a link to a file with which to reproduce the problem.
-->

#### What did you expect to happen?

#### What happened instead?

#### Did the same happen when restarting or reinstalling CliqRex?

<!--
Test if you can reproduce your problem after a restart.
-->

#### Version of OctoPrint

<!--
Can be found in the lower left corner of the about section. ALWAYS INCLUDE.
-->

#### Browser and version of browser, operating system running browser

<!--
If applicable, always include if unsure.
-->

#### Screenshot(s)/video(s) showing the problem:

<!--
If applicable. Always include if unsure or reporting UI issues.
-->

I have read the FAQ.
```
