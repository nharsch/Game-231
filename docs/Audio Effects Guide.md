## EQ

## Compression
![[Compression Graph.png]]

### Threshold
The db level at which the volume reduction will kick in. 

### Ratio
The amount of gain reduction applied to signal over threshold.

For instance, with a 2:1 ratio, the gain is reduced by half. For 2 db over threshold, output gain will be 1, for 10db over, 5db out, etc. For 10:1, gain will be reduced by 90%, for 10db over threshold, 1db will go out.

### Attack
Time, usually in milliseconds, that the compression will start one the level has gone over the threshold. This is useful if you want to keep _some_ of the attack of a signal.

### Release
Time, usually in milliseconds, that the gain reduction will stop after the signal has dropped below the threshold. If compression sounds "choppy", often slowing the release time will make the effect sound smoother.

## Reverb

## Delay