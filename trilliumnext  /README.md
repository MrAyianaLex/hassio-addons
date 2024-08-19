## Installation


1. [Add my Hass.io add-ons repository][repository] to your Hass.io instance.
1. Install this add-on.
1. Click the `Save` button to store your configuration.
1. Start the add-on. It will fail, that is ok
1. ssh in to your home assistant and run `chmod 2777 /2effc9b9/trilliumnext`
1. Start the add-on.
1. Check the logs of the add-on to see if everything went well.
1. Go to your local homeassistant IP:port admin port or ingress.
1. Follow directions

```
port : 8000 #port you want to run admin interface on.
```

Webui can be found at `<your-ip>:port` or ingress.
