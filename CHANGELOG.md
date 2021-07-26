# Changelog

## [v0.3.1] - 2021-07-26

### Fixed

- Fixed comments for `ChartView` `bar_label_visible`, `bar_label_position`, `point_visible`, `point_label_visible` fields

## [v0.3.0] - 2021-06-12

### Changed

- Type of `ChartScale.domain` changed to one of `DomainNumeric`, `DomainCategories`
- Removed `x_scale`, `y_scale` fields from `ChartView`

## [v0.2.0] - 2021-05-31

### Changed

- Types of some fields of `ChartSizes`, `ChartMargins`, `ChartScale`, `ChartView` have been changed to optional

## [v0.1.1] - 2021-05-30

### Fixed

- Removed unused imports

## [v0.1.0] - 2021-05-20

### Changed

- Renamed `ChartViewBarsValues.BarsValues` to `ChartViewBarsValues.BarsDataset`
- Renamed `ChartViewPointsValues.PointValues` to `ChartViewPointsValues.Point`

## [v0.0.1] - 2021-05-10

First release of lc-proto specifications

### Added 

- Added `api_service` specification for public API
- Added `chart` specification with chart options
- Added `color` specification with color options
- Added `renderer_service` specification for renderer API
- Added `scale` specification to configure band and linear scales
- Added `view` specification to configure area, horizontal and vertical bars, line, scatter views
- Added `view_values` specification to configure bars, points and scalar views values
