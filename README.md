# apparmor
AppArmor profiles for ddnet


Move the profiles into ``/etc/apparmor.d``

Verify they show up in ``aa-status``

After updating the profile file run ``systemctl reload apparmor.service``

If the ddnet server stops working check ``dmesg`` for errors.
