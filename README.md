# ZeroNet in Godot

Run an embedded copy of ZeroNet in your Godot game.

## Install

## Start ZeroNet

To start a running copy of ZeroNet, use:

```
ZeroNet.start()
```

You may also specify an optional port:

```
ZeroNet.start(12345)
```

The default port is `43110`.

## Stop ZeroNet

To stop the currently running copy of ZeroNet, use:

```
ZeroNet.stop()
```

If ZeroNet is not currently running, or if an instance of ZeroNet is running that wasn't started by this plugin, this is a no-op.