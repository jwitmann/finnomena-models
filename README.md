# finnomena-models

Go data types for the Finnomena.com API.

## Installation

```bash
go get github.com/jwitmann/finnomena-models
```

## Usage

```go
import "github.com/jwitmann/finnomena-models"

fund := models.Fund{
    FundID:    "F000001",
    ShortCode: "TEST-A",
    NameTH:    "Test Fund",
}
```

## Types

This package provides data types for Finnomena API responses including:
- Fund, FundsResponse - Fund list and details
- BarsResponse - Historical price data (OHLCV)
- FundLatest - Latest NAV
- FundPerformance - Performance metrics
- FundOverview - 3D metrics (PP, RR, DD)
- FundFee - Fee structure
- FundPortfolio - Portfolio composition

## Related

- finnomena-go - API client for Finnomena.com

## License

MIT
