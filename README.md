# LuSEE-Night Documentation

## About

This site is under development. It is designed
to be a hub for LuSEE documentation, mostly software-related
but suitable for other materials as well.

## NGINX deployment

```bash
# On Debian/Ubuntu
sudo service nginx restart # ...or some other service command
```

To extract content of the site in order to deploy it
on an arbitrary server, using the ```httrack``` utility is recommended,
for a specific reason -- utilities such as ```wget``` modify HTML anchor
names (```#```) in a way that is not compatible with the current version
of Bootstrap.

## "Internal" pages

Pages meant to be accessible by authorized users only are terms "internal".
