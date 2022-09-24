# Highcharts Heatmap
This modifies the [Highcharts Column Chart](https://github.com/teochewthunder/hsbar) to form a line chart based on the same data.

## Changes
- Instead of displaying a list of seasons, a list of statistic types will be used.
- Instead of showing player performance based on seasons for all players, we will show all player data by season data in a two-dimensional chart, based on the statistic type selected.

## Requirements
- Added include link to the heatmap library.
- The data used in the chart is an array of arrays. Each sub-array has:
    - `x`: the season name
    - `y`: the player name
    - `val`: the statistic
- Function renaming and text changes.
