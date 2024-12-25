# Changes

This document tracks changes made to the original SkyPatrol project and my modifications.

## Forked from
- Original project: [SkyPatrol](https://github.com/asas-sn/skypatrol.git)
- Modifications by olgavoz1971

## [Unreleased]
### Fixed
- **LightCurveCollection**: Added a check for empty `self.data` to prevent errors when the dataset is empty. This fix was applied to ensure the class works smoothly even when no data is available. (By Olga Vozyakova)
- **SkyPatrolClient**: Added a check to ensure that `chunks` is not empty before concatenating data. This prevents errors in case of an empty result set. (By Olga Vozyakova)

## [1.0.1] - 2024-12-25
### Added
- Enhanced error handling for missing data in the `LightCurveCollection` class.
- Prevent crashes due to missing data by checking for empty datasets before applying transformations.
- Fixed issue with empty `chunks` in `SkyPatrolClient._get_curves`.

## [1.0.0] - 2024-12-25
### Initial release
- Forked from the original SkyPatrol project and made the first set of modifications.
