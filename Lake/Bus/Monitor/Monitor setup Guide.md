## Routing

`Aux N` should be connected to the `Bus N`. It shall be post-fader connection.

![[Aux Bus Routing.png]]

## Sends - signal source

See [[Signal Flow]].

We don't want to use [[Signal Flow|Post Fader]], since otherwise [[Terms|FOH]] fader would affect monitor level.

![[Sends - types.png]]

Nor do we want this to be [[Signal Flow|Pre Fader]] for vocalists, since it includes [[Compressor|Compression]], and singers will constantly fight the compressed sound and ask to turn up the monitor level.

The safer setting for vocal is [[Signal Flow|Pre EQ]]. This way [[Equalizer|EQ]] changes for [[Terms|FOH]] won't cause any [[Feedback]] in the monitor.

## Sends - send it

From sends tab:
![[Sending channel sound to monitor bus.png]]


From mixer tab:
![[Sending sound to monitor bus - from mixer tab.png]]

Dedicated bus mix:
![[Sending sound to monitor bus.png]]

