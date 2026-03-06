# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-03-06

### Added
- Initial release
- Complete data types for Finnomena API:
  - `Fund`, `FundsResponse` - Fund listings
  - `BarsResponse`, `Bar` - Historical price data
  - `FundLatest`, `FundLatestResponse` - Latest NAV
  - `FundPerformance`, `FundPerformanceResponse` - Performance metrics
  - `FundOverview`, `FundOverviewResponse` - 3D metrics
  - `FundFee`, `FundFeeResponse` - Fee structures
  - `FundVerify`, `FundVerifyResponse` - Period verification
  - `FundPortfolio`, `FundPortfolioResponse` - Portfolio data
  - `SymbolInfo` - Trading symbol metadata
  - Supporting types: `Fee`, `Metric`, `YearlyReturn`, `PortfolioSection`, `PortfolioItem`

### Features
- Full JSON struct tags for serialization
- Clean, idiomatic Go types
- Zero dependencies

[1.0.0]: https://github.com/jwitmann/finnomena-models/releases/tag/v1.0.0
