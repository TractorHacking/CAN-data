# Day 3 with the tractor

Upon finding the "Segmented Capture" capability of our scope, the breadth of data we captured greatly improved.

## Data Issues

idle_light_unplugged_on.csv and startUp.csv did not save properly on the scope, the last line of the data was corrupted and the full ~10 seconds were not captured.

Data corruption corrected in commit [617e890](https://github.com/TractorHacking/CAN-data/commit/617e890fc38a7b6e81d57afe9a6e64cb6880e031)
