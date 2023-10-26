# execute fox command

Sends a command to all fox entities that are matched by the given selector. This
block uses EntitySelectors from this extension and not TargetSelectors from the mobs
category.

```sig
mobEvents.executeFoxCommand(mobEvents.createSelector(), Fox.TransformIntoABaby)
```

The blocks in this extension send mob events using the `/event` slash command. Not all mob
events cause an immediate reaction, some configure the behavior of the mob instead. Try
experimenting with events in a variety of situations to see what happens!

## Parameters

* **selector**: A EntitySelector specifying which entities to send the command to
* **command**: A Fox command to send to the selected entities

```package
makecode-minecraft-mob-events=github:microsoft/makecode-minecraft-mob-events
```
