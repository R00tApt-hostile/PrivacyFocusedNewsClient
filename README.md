## Features

1. **Privacy Focused**:
   - No tracking
   - Option to clear history on exit
   - Offline mode available
   - Local caching with control over cache size

2. **Multiple News Sources**:
   - Default sources include BBC, Reuters, AP News, Privacy International, and The Guardian
   - Ability to add, edit, and remove custom sources

3. **Media Handling**:
   - Download images from articles
   - Save media to local files
   - Caching system for offline viewing

4. **User Interface**:
   - Multiple color themes (Dark, Light, Solarized)
   - Responsive layout
   - Article categorization and filtering
   - Bookmarking/saving articles

5. **Additional Features**:
   - Auto-refresh with configurable interval
   - SQLite database for article storage
   - Threaded operations to prevent UI freezing

## Requirements

- Python 3.7+
- Required packages:
  ```
  feedparser
  beautifulsoup4
  requests
  pillow
  pytz
  ```

Install dependencies with:
```
pip install feedparser beautifulsoup4 requests pillow pytz
```

## How to Use

1. Run the script with `python news_client.py`
2. Browse news sources in the left sidebar
3. Select articles to view details
4. Use the menu to customize settings, change themes, and manage sources

The application will create a configuration directory at `~/.privacy_news_client` to store settings, cached articles, and downloaded media.
