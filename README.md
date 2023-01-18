## HomeAssistant, Easee, ID.4 Smart Charging + Load Balance ##
Was based on https://github.com/kotope/ha_nordpool_cheapest_hours, along with the comments section in https://www.creatingsmarthome.com/index.php/2022/09/17/home-assistant-nord-pool-spot-prices-and-how-to-automate-devices-for-cheapest-hours/, but close to 100% is rewritten.

This package uses 
* Nordpool (https://github.com/custom-components/nordpool)
* Easee (https://github.com/fondberg/easee_hass)
* Volkswagen We Connect ID (https://github.com/mitch-dc/volkswagen_we_connect_id)

TODO:
* If car_ready_at is tomorrow AND tomorrow_valid=false, only use today - CHECK IF DONE?
* Implement deadband when amp is close to max to avoid ping pong up and down
* Comments/documentation
* Possibly making code more general and less specific to my setup
* Implement manual mode - off (already in place-smartcharge switch?) - and without id4 integration (manual SoC and target SoC sliders)







## Support the developer?
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/fransakeson)

