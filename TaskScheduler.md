You can create a scheduled task that will run when your computer is unlocked:

Start > Administrative Tools > Task Scheduler
left pane: select Task Scheduler Library
right pane: click Create Task... (NOTE: this is the only way to get the correct trigger)
in the Create Task dialog:
General tab -- provide a name for your task
Triggers tab -- click New... and select On workstation unlock
Action tab -- click New... and click Browse... to locate your script
Conditions tab -- uncheck Start the task only if the computer is on AC power
