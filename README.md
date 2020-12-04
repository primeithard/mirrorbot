## Feature

* Set as Private (Using Password Verification)
* Able to Use in Groups.
* Able to Mirror Larger Files Than 2GB (But Uploads as Splitted Due Telegram Max Upload Limit Is 1.95GB).
* Split As Video (.mp4, .mkv, .avi, .webm, .wmv, .mov)
* Upload Files as Media or as Document
* Upload Files As A Single Zip File.
* Custom Thumbnail Supports.
* Default Torrent Tracker.
* Customise Language (Default Is English).
* ConfiguratioN Using Environment Variable.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Folder Structure

* `/` : development detail and deploy config
* `/bot` : module root dir
    * `__init__.py` : bot config
    * `__main__.py` : register handler then run bot
    * `config.py` : create configuration and configurable from env var
* `/bot/handler` : message handler
* `/bot/locals` : localization and default is en
* `/bot/plugins` : third party implementation
