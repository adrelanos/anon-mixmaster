# Mixmaster over Tor for Anonymity Distribution Workstations #

Allows tunneling mixmaster though Tor.

Allows running mixmaster-update without sudo for better usability.

Ships Mixmaster config file /etc/skel/.Mix/mix.cfg.
## How to install `anon-mixmaster` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org stretch main" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `anon-mixmaster`.

```
sudo apt-get install anon-mixmaster
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `anon-mixmaster` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Payments ##

`anon-mixmaster` requires [payments](https://www.whonix.org/wiki/Payments) to stay alive!
