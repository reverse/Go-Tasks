# Go-Routine-Control

The issue with Go routines and their use in tasks (in sneaker bots) is stopping them when a user requests it. As you know modern bots have stop functions for each task, which sparked me to create this for Go.

## Use of channels

I have used channels to signal a task, or go routine to stop. Two new channels are created when you start a task:
 - TaskIDStop
 - TaskIDStopped
