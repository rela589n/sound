Subgroup is essentially a bus, which outputs sound to the main LR, compared to [[DCA groups]], which doesn't give intermediary layer. 
It allows us to group sources together to have some common control on them.

![[Subgroup signal flow.png]]


## Bus setup

Make two buses to be subgroups for every channel:

![[Make bus the subgroup - for channel.png]]

Or, on the bus view:

![[Make bus subgroup.png]]

Link two subgroups to make a stereo subgroup:

![[Making stereo subgroup.png]]

Output sound from subgroups to the main Stereo LR:
![[Sending subgroup output to LR master.png]]

## Channels setup

Prevent individual channels we want to  group from being sent to the main LR directly:

![[Preventing the channel output from being sent to LR directly.png]]

Then, finally we add these channels to the group and tweak Left-Right balance:

![[Adding channels to the group and adjusting the balance.png]]

## Mixing

Now, in Bus5 (or Bus6 - no matter, it's linked) we can adjust the group level.

![[Mixing the subgroup.png]]

We can attach the [[Compressor]] to the bus, [[Equalizer|EQ]] it, insert some effect, etc.

