![Logo](admin/pvforecast.png)

# ioBroker.pvforecast

![Number of Installations](http://iobroker.live/badges/pvforecast-installed.svg)
![Number of Installations](http://iobroker.live/badges/pvforecast-stable.svg)
[![NPM version](http://img.shields.io/npm/v/iobroker.pvforecast.svg)](https://www.npmjs.com/package/iobroker.pvforecast)

![Test and Release](https://github.com/iobroker-community-adapters/iobroker.pvforecast/workflows/Test%20and%20Release/badge.svg)
[![Translation status](https://weblate.iobroker.net/widgets/adapters/-/pvforecast/svg-badge.svg)](https://weblate.iobroker.net/engage/adapters/?utm_source=widget)
[![Downloads](https://img.shields.io/npm/dm/iobroker.pvforecast.svg)](https://www.npmjs.com/package/iobroker.pvforecast)

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

Provides forecast data from [forecast.solar](https://forecast.solar), [Solcast](https://solcast.com/) or [SolarPredictionAPI](https://rapidapi.com/stromdao-stromdao-default/api/solarenergyprediction/)

## Documentation

[🇺🇸 Documentation](./docs/en/README.md)

[🇩🇪 Dokumentation](./docs/de/README.md)

## Credits

- Logo (Sun): https://pixabay.com/de/vectors/sonne-wetter-wettervorhersage-157126/

## Changelog
<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->
### **WORK IN PROGRESS**
* (klein0r) Summary channel should not be deleted

### 2.7.0 (2023-05-09)
* (klein0r) Request forecast data in correct timezone
* (bluefox) Type of the `summary` object was changed to `device`

### 2.6.0 (2023-03-09)
* (arteck) chart summary for more strings
* (klein0r) Fixed charting summary
* (klein0r) Rounded values in JSON summary

### 2.5.2 (2023-03-08)
* (klein0r) Fixed error when weather data could not be fetched

### 2.5.1 (2023-01-13)
* (klein0r) Fixed JSON table when using solcast

### 2.5.0 (2023-01-11)
* (klein0r) Added hourly values for energy
* (Apollon77) Added Sentry for crash reporting
* (klein0r) Dropped Admin 5 support
* (klein0r) Added Ukrainian language

## License
MIT License

Copyright (c) 2021-2023 Patrick-Walther
                        Matthias Kleine <info@haus-automatisierung.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
