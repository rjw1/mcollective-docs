---
layout: ondieting
title: Overview
---

Overview
--------
The Marionette Collective aka. mcollective is a framework to build server orchestration 
or parallel job execution systems.

Primarily we'll use it as a means to programmatically execute actions on clusters of servers. 
In this regard we operate in the same space as tools like Func, Fabric or Capistrano.

We've attempted to think out of the box a bit designing this system by not relying on central 
inventories and tools like SSH, we're not simply a fancy SSH "for loop". MCollective uses modern 
tools like Publish Subscribe Middleware and modern philosophies like real time discovery of network 
resources using meta data and not hostnames. Delivering a very scalable and very fast parallel 
execution environment.

We've focused on catering for the needs of enterprises and large deploys, we have pluggable Authentication, 
Authorization and Auditing capabilities that sets us apart from other tools in this space.

Read the <a href="/introduction.html">Introduction</a> page for a full 
introduction about what you can do with mcollective and some of our goals and approaches.

We've recorded a quick screencast that introduces the main elements, please view it below - maximise it for
best viewing.

<embed src="http://blip.tv/play/hfMOgenPYQA" type="application/x-shockwave-flash" width="600" height="301" 
allowscriptaccess="always" allowfullscreen="true"></embed>
