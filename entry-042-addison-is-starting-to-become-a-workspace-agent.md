# Addison Is Starting to Become a Workspace Agent

The next part of the Addison catch-up is probably the hardest one to explain simply.

A lot of the recent work has been about making Addison feel less trapped in conversation.

That does not mean I want her to become an unbounded agent that can just do whatever she wants on my machine. That has never been the goal.

The real goal is narrower and more useful:

I want to be able to point Addison at a workspace and have her understand, “this is the place we are working.”

Inside that scope, she should eventually be able to inspect files, create folders, draft documents, write new files, run safe checks, and keep track of what happened without me having to manually carry every tiny step.

That sounds simple from the outside.

It is not simple if you care about authority.

A normal coding agent can feel powerful because it can touch a repo, run commands, edit files, and keep moving. But Addison is not being built around the assumption that capability automatically means permission.

That is the line I have been working through.

The recent work has started putting the foundation under that idea.

Addison now has the early shape of a workspace envelope. That means the system can represent a declared workspace instead of treating the whole machine like open territory. It can classify requested actions. It can produce receipts. It can do bounded read/list work. It can create a new folder or write a brand-new file inside the active scope. It can record metadata about context and artifacts. It can start forming a run/event trail. It can execute narrow, reviewed command profiles for safe inspection and testing.

That last part matters a lot.

There is a big difference between “run this exact reviewed profile under constraints” and “here is a shell, do whatever.” Addison is moving toward the first one, not the second one.

This is the kind of progress that is easy to overstate, so I want to be careful.

This is not broad autonomy.

This is not arbitrary terminal access.

This is not plugin import.

This is not background scheduling.

This is not Addison silently changing memory or truth.

It is the beginning of a governed workspace layer.

That might sound less exciting than saying “I made an agent,” but honestly, this is the part I care about more.

I do not just want Addison to act.

I want Addison to act inside a structure that can explain what was allowed, what was blocked, what was only a candidate, what changed, and what still needs me.

That is the shape of the project right now.

The goal is not to remove the human from the loop.

The goal is to stop making the human carry every piece of the loop manually.
