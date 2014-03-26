# nhlbot

## About

nhlbot is a Python IRC bot based on [CloudBot](http://git.io/cloudbot) which is based on [Skybot](http://git.io/skybot) by [rmmh](http://git.io/rmmh).

## Using nhlbot

### Install

Before you can run the bot, you need to install a few Python dependencies. LXML is required.

These can be installed with `pip` (The Python package manager):

    [sudo] pip install -r requirements.txt
    
If you use `pip`, you will also need the following packages on linux or `pip` will fail to install the requirements.
   ```python, python-dev, libxslt-dev, libxml2-dev.```

#### How to install `pip`

    curl -O https://raw.github.com/pypa/pip/master/contrib/get-pip.py # or download with your browser
    python get-pip.py

### Run

Before you run the bot, rename `config.default` to `config` and edit it with your preferred settings.

Once you have installed the required dependencies and renamed the config file, you can run the bot! Make sure you are in the correct folder and run the following command:

`python bot.py`

## License

CloudBot is **licensed** under the **GPL v3** license. The terms are as follows.

    nhlbot

    Copyright © 2011-2013 Andrew Vehlies

    nhlbot is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    nhlbot is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with nhlbot.  If not, see <http://www.gnu.org/licenses/>.
