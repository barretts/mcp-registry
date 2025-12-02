# Omni Tool MCP Server

A universal conversion and transformation toolkit for developers.

## Tools

| Tool | Description |
|------|-------------|
| **convert** | Universal converter: time, colors, units (length, weight, temp, digital, CSS, crypto, duration, speed, area, volume) |
| **compare** | Compare values with automatic unit conversion |
| **transform_string** | Detect encoding, decode, and transform strings |
| **analyze_color** | Parse any color format and get all conversions + accessibility info |
| **inspect_jwt** | Decode JWT tokens without verification |
| **generate_mock_data** | Generate UUIDs, hex strings, IP addresses |
| **calculate_statistics** | Calculate mean, median, min, max, sum |

## Convert Examples

```
convert "now"                    → timestamps, JS Date(), moment.js formats
convert "in 4 days"              → future date with all formats
convert "10" unit:"px"           → CSS units (rem, em, pt, %)
convert "60" unit:"mph"          → speed (km/h, m/s, knots)
convert "0.034" unit:"btc"       → crypto (satoshi, mBTC)
convert "#FF5733"                → all color formats
```

## Color Formats Supported

**Input:** Hex (#RGB, #RRGGBB, #RRGGBBAA), RGB, RGBA, HSL, HWB, LAB, LCH, Oklab, Oklch

**Output:** All above formats plus CMYK, HSV, ANSI256, accessibility contrast ratios

## Unit Categories

- **Length:** m, km, cm, mm, mi, ft, in, yd
- **Weight:** kg, g, mg, lb, oz, stone
- **Temperature:** C, F, K
- **Digital:** B, KB, MB, GB, TB
- **CSS:** px, rem, em, pt, %
- **Crypto:** BTC, satoshi, mBTC, ETH, gwei, wei
- **Duration:** ms, sec, min, hr, day, week
- **Speed:** mph, km/h, m/s, ft/s, knots
- **Area:** sq ft, sq m, acres, hectares
- **Volume:** ml, L, gal, fl oz, cups, pints

## Documentation

https://github.com/barretts/mcp-omni-tool
