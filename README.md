# HomeAssistant, Easee, WeConnect Smart Charging + Load Balance #
Was based on https://github.com/kotope/ha_nordpool_cheapest_hours, along with the comments section in https://www.creatingsmarthome.com/index.php/2022/09/17/home-assistant-nord-pool-spot-prices-and-how-to-automate-devices-for-cheapest-hours/, but close to 100% is rewritten.

## This package uses ## 
* Nordpool (https://github.com/custom-components/nordpool) - Needed to figure out cheapest period.
* Easee (https://github.com/fondberg/easee_hass) - Needed to control charger. Start, stop and set current. Should be easy to replace with an integration of your choice.
* Volkswagen We Connect ID (https://github.com/mitch-dc/volkswagen_we_connect_id) - Only needed to know current and target SoC. Should be easy to replace with an integration of your choice.

## Install ##
Download yaml package to your homeassistant configuration directory and add this block to `configuration.yaml`

```
homeassistant:
  packages:
    ha_ev_charging: !include ha_ev_charging.yaml
```

## Configuration / Setup ##
See initial comments in `ha_ev_charging.yaml`

## To do ##
* Implement deadband when amp is close to max to avoid ping pong up and down
* More comments/documentation




## Support the developer?
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/fransakeson)

