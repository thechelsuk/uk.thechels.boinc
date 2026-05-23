---
title: BOINC
layout: page

---

BOINC is a platform that allows computers all round the world to contribute their spare computing capacity to run
distributed applications. Several of those involved with [TheChels.org](https://thechels.net/tag/thechels/) contribute
their computers in such a way.

Distributed applications are largely run by Universities to research fields such as Biology & Medicine, Earth Sciences,
Mathematics or Physics & Astronomy. To cut a very long story short, there are two projects we'd like to talk about;
Rosetta and World Community Grid.

[Rosetta](https://boinc.bakerlab.org/rosetta/) - Rosetta is described at About
[Rosetta](https://boinc.bakerlab.org/rosetta/rah/rah_about.php) with useful Wiki links that give an indication of what
Protein folding is and how it relates to disease. Rosetta doesn't attempt to look for cures, but tries to replicate how
proteins fold (or mis-fold) so that it can seek to improve on nature or find binding proteins that may be able to
neutralise disease in the body.

Disease related research includes work that will help Malaria, Anthrax, HIV, Herpes, alzheimer's, Cancer, Prostate
Cancer, Bird Flu and Influenza. More recent work has been targeted toward SARS-CoV-2, the virus that causes COVID19.
[The Rosetta promotional video is here](https://www.youtube.com/watch?gl=GB&v=GzATbET3g54)

[World Community Grid](https://www.worldcommunitygrid.org/) - World Community Grid (WCG) does similar work, but is an
umbrella project for several areas of research, currently Africa Rainfall, Microbiome Immunity, Childhood cancer,
Tuberculosis, AIDS and Mapping Cancer. The new Open Pandemics sub-project works on COVID19 treatments. [Their
promotional video is here](https://www.youtube.com/watch?v=dOFOh4iXQ7Q)

The software is 100% safe, and will not intrude on your normal computer use as it utilises it when you're not.

## Installing BOINC

Visit the [BOINC homepage](https://boinc.berkeley.edu/) and click the Download option. This should take you to a page
that offers you the correct BOINC version to match your OS.

Note there are different versions for Windows 32bit and 64 bit, similarly for Linux x86 or x-64 or Mac OS X. If you
don't think it's picked the right one, click "All versions" on this page and you can confirm or select the best option
for you.

Install it as a shared or service installation, ensure it is NOT set as the default screensaver (more on that later),
and set it to launch on completion.

### Attaching to Rosetta

When it starts, make sure you're in Advanced View so that you have menus at the top of the window. Click the Tools menu
to select "Add project...". Select Rosetta@home as your project, ensure you're set as a New User, decide (and remember)
a password and you'll be connected.

On attachment, work units will be downloaded and will be visible under the Tasks tab. One task will run concurrently for
each CPU core you have, so a quad core will run 4, dual core 2 etc, older single core just one.

Most people, who are interested, will be keen that their machine operates normally as quickly as it can and might be
concerned that CPU usage (as shown in Windows Task Manager) is at 100% and will be forever more while BOINC is running.

The key is that while all tasks use up ALL unused clock cycles, they run at "low priority" so the moment you move the
mouse, type, run a program, watch a video, play music, whatever, priority seamlessly moves away from BOINC and lets you
do it without any slowdown.

I ran out of tasks once and noticed no speed up, then when more came down I noticed no slowdown, so I'm pretty confident
you won't either.

Rosetta tasks run for 8 hours by default. When they complete they're sent back automatically and more tasks come down.
As the manager program becomes used to the rate you complete the tasks it'll grab a default 0.25 days worth of tasks in
case of either loss of internet connection or a temporary absence of available tasks.

If you click a task you can select the "Show Graphics" button on the top left to see a visualisation of the work being
done. It's this animation that can be set as your screensaver if you want, though bear in mind that it uses CPU time to
display and slows the progress of the calculation.

### Adjusting settings

Now tasks are running, from either the Project or Tasks page, select the Rosetta project or task and click "Your
account" from the list of websites that appear on the left. Enter the email and Password details you used when
installing BOINC.

In the "Account Information" section of the page click to change "other account info" to modify your displayed name
rather than have your email address on display, chose your country and update info. No other fields need to be changed
here and you can be confident your email address isn't misused.

Finally, find the TheChels Team page and select "Join this team" and all the essentials are complete.

After a while you may notice on the Boinc Manager project page that a figure appears under "Work done". That's because a
credit figure for your task will be awarded to you, which varies from task to task and from project to project. You can
view the progression of these credits on the Statistics tab. A stats site also exists which, after a day or two, will
begin showing your position among the 4 million other contributors to BOINC projects.

Once you feel settled with this project - probably best to leave it for a few days - use the Tools menu to attach to
World Community Grid (or not - as you wish). The only difference is that tasks come down under different application
names within the WCG project and the default run-times will vary from 2 to 10 hours.

#### Troubleshooting

There are several other issues you may want to know in advance - just ask [@sidcelery](https://x.com/sidcelery) on X/Twitter

If there's one issue I'd bring up first it's that the constant processing can find the weak spots in a flaky or
memory-constrained machine. You should have a minimum 1Gb RAM for a single-core machine, 2Gb RAM on a dual-core machine
and 4Gb RAM on a quad-core.

Below are a list of further Wiki links on the general subject.

- [BOINC](https://en.wikipedia.org/wiki/Berkeley_Open_Infrastructure_for_Network_Computing)
- [Distributed computing](https://en.wikipedia.org/wiki/Distributed_computing)
- [List of Distributed computing projects - Wiki](https://en.wikipedia.org/wiki/List_of_distributed_computing_projects)
- [Platforms supported by projects](httpss://boinc.berkeley.edu/projects.php)
