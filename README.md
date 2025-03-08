# facebook-character-analizer

Scrapes profile data and posts from facebook and sends them to an llm api for character analysis.

## Setup

Uses `selenium` with chromium and the crome webdriver. Install chromium with `sudo snap install chromium chromium-ffmpeg` and the webdriver with `sudo apt install chromium-chromedriver`.

Instead of scraping the live page it would be better to scape a downloaded version.
