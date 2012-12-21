# NSSplitView-Animatable

NSSplitView Category to perform simple animations with dividers using Core Animations.

You can animate one divider at time or perform a grouped animations with more dividers.
Available methods are:

``` objective-c
- (BOOL) setPosition:(CGFloat)position ofDividerAtIndex:(NSInteger)dividerIndex animated:(BOOL) animated;
- (BOOL) setPositions:(NSArray *)newPositions ofDividersAtIndexes:(NSArray *)dividerIndexes;
```

It also have a simple method to get a divider current position:
``` objective-c
- (CGFloat) positionOfDividerAtIndex:(NSInteger)dividerIndex;
```