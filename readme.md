Demonstrates how to figure out when a one-shot particle2d sequence is fully complete.

Steps:
1. wait for emitting to turn back to false
2. after emitting is false again, wait for particle2d.lifetime seconds for the last set of particles to fully finish

You can turn emitting back on as soon as it becomes false but it seems to not complete a fully cycle properly unless you wait for the last one to be fully complete.

![Screenshot of demo in action](action_screenshot.png?raw=true "Screenshot of demo in action")
