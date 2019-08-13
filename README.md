RefreshRateTester
====================

This is a slightly modified version of shurcooL's RefreshRateMultitool.
This program displays images in sync with your monitor's refresh rate so you can test for frameskipping and artifacts.

![RefreshRateTester](https://i.imgur.com/5P5632i.gif)

```
Usage: RefreshRateMultitool.exe [columns rows]
 -columns - if specified, sets the number of columns, default 6
 -row     - if specified, sets the number of rows, default 1
```

This tool is more performant and consistent than browser-based tests.
See https://github.com/shurcooL-legacy/RefreshRateMultitool for more information.

*Do not use if sensitive to flashing lights*

Version 1.0
- Removed requirement for user to type "i agree" on launch
- Defaults to 6x10 grid
- Defaults to larger window size
- Minor documentation changes
- Executable provided for Windows only
