# Changelog

### v1.3.13

28.03.2019.

**Fixed**

* Fixed SVG stroke color property name (from `strokColor` to `color`)

-----

### v1.3.12

12.02.2019.

**Fixed**

* Fixed default params in transform methods.

-----

### v1.3.11

17.12.2018.

**Added**

* Added `onPlxStart` and `onPlxEnd` [callbacks](https://github.com/Stanko/react-plx/pull/48)

-----

### v1.3.10

13.12.2018.

**Changed**

* Updated `window-scroll-manager` dependency.

-----

### v1.3.8 and v1.3.9

02.09.2018.

**Changed**

* Breaking change - corrected typo `bellow` -> `below`.

**Updated**

* Updated readme.

-----

### v1.3.6 and v1.3.7

14.07.2018.

**Fixed**

* Fixed `setState` getting called with `null` as a param

-----

### v1.3.2, v1.3.3, v1.3.4 and v1.3.5 (it was a hard day)

12.07.2018.

**Updated**

* Updated [window-scroll-manager](https://github.com/Stanko/window-scroll-manager) version.
* Added version git tags

-----

### v1.3.0 and v1.3.1

10.06.2018.

**Changed**

* Refactored a little bit, moved update logic outside of the component. Updated dependencie.
* Moved 'animated-scroll-to' to dev dependencies

-----

* Moved main update method outside of the component class. Updated dependencies.

### v1.2.2

09.06.2018.

**Added**

* Added `fill` and `strokeColor` to the list of the color properties that can be animated.


-----

### v1.2.0

26.05.2018.

**Changed**

* Replaced `componentWillReceiveProps` with `componentDidUpdate` to address changes introduced with React v16.3


-----


### v1.1.3

26.05.2018.

**Added**

* This changelog.

**Fixed**

* Added a check if element is rendered before doing animation, related [issue](https://github.com/Stanko/react-plx/issues/17).


-----

For changes prior version 1.1.3 please check the [commit list](https://github.com/Stanko/react-plx/commits/master).
