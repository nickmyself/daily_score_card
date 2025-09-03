# Daily Trading Score Card

A web-based tool for analyzing trading performance using CSV data from trading accounts.

## Live Demo
https://nickmyself.github.io/daily_score_card/

## Features

- **Multi-Account Support**: Upload CSV files from up to 2 trading accounts
- **R Multiple Analysis**: Calculate risk-adjusted returns using customizable R values
- **Dual Statistics View**: View performance in both dollar amounts and R multiples
- **Privacy-Focused Design**: Dollar amounts are hidden by default with optional toggle
- **Trade Aggregation**: Automatically groups partial fills into complete trades
- **Ticker Summary**: Detailed breakdown of performance by individual symbols
- **Responsive Design**: Clean, professional interface that works on all devices

## How to Use

1. **Upload Files**: Select CSV files from your trading platform(s)
2. **Set R Multiple**: Enter your risk per trade amount (e.g., 100 for $100 risk)
3. **Analyze**: Click "Analyze Trading Data" to generate your report
4. **Toggle Views**: Use the switch to show/hide dollar amounts and focus on R multiples

## Statistics Displayed

### Overall Performance
- Total PnL ($ and R multiples)
- Win/Loss counts
- Average win/loss amounts
- Win rate percentage
- Average risk-reward ratio

### Ticker Breakdown
- Individual trade results by symbol
- Color-coded profit/loss indicators
- Both dollar and R multiple views

## CSV Format Requirements

The tool expects CSV files with the following columns:
- `Symbol`: Trading symbol
- `Side`: Trade side (B for Buy, SS for Short Sell)
- `Qty`: Quantity traded
- `P / L`: Profit/Loss amount
- `ECNFee`: ECN fees (optional)
- `Time`: Trade timestamp

## Privacy & Security

- All data processing happens locally in your browser
- No data is sent to external servers
- Dollar amounts are hidden by default to maintain focus on risk management
- Files are processed in memory and not stored

## Browser Compatibility

Works with all modern web browsers including Chrome, Firefox, Safari, and Edge.
