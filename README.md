# Push News Br CLI

A command-line interface (CLI) tool that displays Brazilian news headlines from UOL along with real-time currency rates (USD/BRL and BTC/USD) directly in your terminal.

## Features

- Live UOL news headlines via RSS feed
- Real-time USD/BRL exchange rate
- Real-time Bitcoin (BTC) price
- Clean terminal interface
- Auto-refresh capability

## Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

## Installation

### Required packages:
```bash
pip install requests
```

### Installing on macOS:
```bash
# Move to your scripts directory
mkdir -p ~/scripts
cp src/news ~/scripts/

# Make executable
chmod +x ~/scripts/news

# Add to PATH (add to .zshrc)
export PATH="$HOME/scripts:$PATH"
alias noticias="news"
```

## Usage

Run the program by typing in your terminal:
```bash
news
# or
noticias
```

Controls:
- Press `r` to refresh the news feed
- Press `q` to quit

## Screenshots

![Terminal Screenshot](screenshots/preview.png)

## Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.