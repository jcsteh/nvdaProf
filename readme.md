# NVDA Profile Viewer

- Author: James Teh &lt;jamie@jantrid.net&gt;
- Copyright: 2026 James Teh
- License: GNU General Public License version 2.0

[Open NVDA Profile Viewer](https://files.jantrid.net/nvdaProf/)

This is a simple web app to view [NVDA screen reader](https://www.nvaccess.org/) performance profiles recorded with [py-spy](https://github.com/benfred/py-spy).
It shows the call tree for the thread you choose.
By default, the stack is inverted so that the deepest calls are at the top of the tree, but you can toggle this.
Each branch is sorted from highest to lowest total count of samples.
The app includes a demo profile so you can see what it looks like.

## Why?
There are much better profile viewers of course.
py-spy can output Speedscope profiles, but Speedscope isn't screen reader accessible.
There's the Firefox profiler for which the call tree is very accessible, but it can't load Speedscope or raw py-spy profiles, and even though it can load chrometrace profiles which py-spy can generate, they don't seem to show the call tree.
So, this at least makes NVDA profiles accessible to those of us who are screen reader users.
