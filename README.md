![OCPP](https://github.com/home-assistant/brands/raw/master/custom_integrations/ocpp/icon.png)

This is a Home Assistant integration for the Grizzl-E Smart charger based on https://github.com/lbbrhzn/ocpp. This is a fork that includes changes to deal with the Grizzl-E OCPP-compliance defects as described in https://github.com/stefanthoss/ocpp-grizzl-e/blob/main/docs/user-guide.md#ocpp-compatibility-issues and https://github.com/lbbrhzn/ocpp/issues/442#issuecomment-1237651231.

This fork (SDB) is further edited to maintain compatibility with Home Assistant updates. This is intended to just be used by the repository owner, and no guarantees about longterm support or functionality are given. After years of struggle with the Grizzl-E smart charger, and occasional unintended package updates that overwrote manual changes, this is now being used by the repository owner.

Most recent changes compared to @stefanthoss version is code updates to address warnings in Home Assistant that `via_device` calls will not be supported in future versions, as well as removing use of `homeassistant.core.Config`.

In case it is useful to any readers, the Grizzl-E charger is configured with 0 seconds Idle. Charger is running firmware 05.653:GCW-10.17-05.3:7452:B29A

* based on the [Python OCPP Package](https://github.com/mobilityhouse/ocpp).
* HACS compliant repository 

Documentation can be found here [home-assistant-ocpp.readthedocs.io](https://home-assistant-ocpp.readthedocs.io)

**💡 Tip:** If you like this project consider buying lbbrhzn a coffee or a cocktail:

<a href="https://www.buymeacoffee.com/lbbrhzn" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/default-black.png" alt="Buy Me A Coffee" width="150px">
</a>
