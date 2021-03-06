---
layout: page
category: walkthrough
title: Administration tasks
is-detailed: false

---

<div id="toc">
Table of Contents
<ol>
    <li><a href="#logging_in">Logging In</a></li>
    <li><a href="#users">Adding Users</a></li>
    <li><a href="#admin-groups">Creating groups and adding users to them</a></li>
    <li><a href="#admin-new-inst">Adding new instruments</a></li>
    <li><a href="#admin-reports">Creating project and monthly reports</a></li>
</ol>
</div>

{% include logging_in.md detailed=page.is-detailed %}

In order to perform the tasks in this section you must be a MISO admin.
Contact your MISO administrator to gain admin status.

<a name="users" href="#" id="toplink">top</a>

# 2. Adding Users

The method of adding users varies by MISO installation.

If you were able to log in at the beginning of this tutorial using a user name and/or password
you chose, you can add new users.

1. On the left hand menu under the _User Administration_ section, click _Users_.
1. Click the _Add_ button at the top left of the table.
1. Enter the new user's login name (all one word), email, and a password.
1. Click _Save_ in the top right corner.

If you were able to log in at the beginning of this tutorial using a user name and password
that you use for other services at your institute, users cannot be manually added by administrators.
Users must be added by IT; once added, users can log in to MISO using their existing credentials
(LDAP or Active Directory).

{% include admin-new-inst.md %}

{% include admin-reports.md %}


< <a href="tutorial-plain-introduction">Introduction</a> | <a href="pindex-plain">Home</a> | <a href="tutorial-plain-boxes">Working with Boxes</a> >
