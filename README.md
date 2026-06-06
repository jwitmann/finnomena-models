# DEPRECATED — finnomena-models

> **This repository is deprecated and no longer maintained.**
>
> The types have been merged into [finnomena-go](https://github.com/jwitmann/finnomena-go) as a subpackage.
>
> **Migrate to:** `github.com/jwitmann/finnomena-go/models`

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Go data types for the [Finnomena.com](https://www.finnomena.com) Thai mutual fund API.

This package was a supporting library for [finnomena-go](https://github.com/jwitmann/finnomena-go). As of the merge, all types live in the `models` subpackage of `finnomena-go`.

## Migration

Update your import path:

```go
// Before
import "github.com/jwitmann/finnomena-models"

// After
import "github.com/jwitmann/finnomena-go/models"
```

All type names remain identical (`models.Fund`, `models.BarsResponse`, etc.).

## Installation (Legacy — Do Not Use)

```bash
# Do not install this deprecated package
go get github.com/jwitmann/finnomena-go/models
```

## Types

This package provides data types for Finnomena API responses:

**Fund Data:**
- `Fund` - Individual fund information
- `FundsResponse` - List of all funds

**Historical Data:**
- `BarsResponse` - OHLCV price bars
- `Bar` - Single price bar

**Fund Information:**
- `FundLatest` - Latest NAV and change
- `FundLatestResponse` - Wrapper for latest data
- `FundPerformance` - Returns, volatility, Sharpe ratio
- `FundPerformanceResponse` - Wrapper for performance data
- `FundOverview` - 3D metrics (PP, RR, DD scores)
- `FundOverviewResponse` - Wrapper for overview data

**Fund Details:**
- `FundFee` - Fee structure
- `FundFeeResponse` - Wrapper for fee data
- `FundVerify` - Available periods for fund
- `FundVerifyResponse` - Wrapper for verify data
- `FundPortfolio` - Portfolio holdings
- `FundPortfolioResponse` - Wrapper for portfolio data

**Supporting Types:**
- `SymbolInfo` - Trading symbol metadata
- `Fee` - Individual fee entry
- `Metric` - PP/RR/DD metric with score
- `YearlyReturn` - Annual return data
- `PortfolioSection` - Portfolio category section
- `PortfolioItem` - Individual portfolio holding

All types include proper JSON tags for seamless serialization.

## Related

- [finnomena-go](https://github.com/jwitmann/finnomena-go) - API client using these types
- [thai-market-data](https://github.com/jwitmann/thai-market-data) - Thai market data sources

## Contributing

This package is primarily a data type library. For API client features, see [finnomena-go](https://github.com/jwitmann/finnomena-go).

## License

MIT License - see [LICENSE](LICENSE) file for details
