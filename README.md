# @frontendmonster/setps

Creates array of numbers from start to end point with specific steps.

## Usage

```javascript
import steps from '@frontendmonster/steps';

steps(0, 5, 1); // [0, .2, .4, .6, .8, 1]
steps(0, 2, 1); // [0, .5, 1]
steps(0, .3, 4) // Error: Can't reach end with 0.3 steps
```
