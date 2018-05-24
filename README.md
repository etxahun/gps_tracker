# gps_tracker
Web application based on Websockets for GPS data visualization through Google Maps API.

## Table of Contents
 - [Installation](#installation)
 - [Configuration](#configuration)
 - [Usage](#usage)
 - [Contributing](#contributing)
 - [References](#references)

## Installation

First of all install replace the following files:
```shell
    $ mv index.html.sample index.html
    $ mv js/main.js.sample js/main.js
```

## Configuration

The following tweaks are needed in order to make it work:

1. Include your Google Maps API key inside the "index.html" file:

  <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY">
</script>

2. Edit your MQTT Broker URL and Websockets PORT:
```javascript
  var MQTTbroker = '<MQTT_BROKER_HOSTNAME>';
  var MQTTport = <Websockets PORT>;
```

## Usage

Open the "index.html" file in your browser:

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## References
