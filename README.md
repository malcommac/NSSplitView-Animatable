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
## Contact

Daniele Margutti

- https://github.com/malcommac
- https://twitter.com/danielemargutti
- https://www.danielemargutti.com
- me@danielemargutti.com

## License

NSSplitView-Animatable is available under the MIT license.
Copyright © 2013 Daniele Margutti
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
