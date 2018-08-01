# Starting a script on reboot

A simple crontab entry for starting a script on reboot might look something like this:

```
@reboot python /home/pi/my_script.py
```

This is the easiest method by far, but it's inflexible and suffers from a few pitfalls you might not realise at first.
