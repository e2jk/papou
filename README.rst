Papou - digital content offloader
=================================

Use case
--------

You get home after a long day. You've taken a number of pictures during the day, and you just want them safe without having to turn on your computer, fiddle with the files on your hard disk.

You pull the memory card from your camera, plug it in the card reader that is linked to your Raspberry Pi, and *voila*, the pictures are getting copied from your card to your disk.

The Pibrella will show you it's working on copying your files using the LEDs, and will buzz when all the content has been copied over from your memory card.

You can either stop here (hey, you're pictures are on your hard drive, in their own folder using today's date), or you can decide to further organize your pictures (e.g. split them into various folders per event).

Should you have multiple hard drives plugged into your Pi, a press of the big red button on your Pibrella will iniciate a rsync-hronization of your principal disk to your other disks(s). That's redundant backups at your fingertip!

Finally, should you have a remote backup location defined, the content from your primary disk will be securely copied over the Internet to that location, without any action from your part. Who said offsite backups had to be complex?

Needed hardware
~~~~~~~~~~~~~~~

* A `Raspberry Pi <http://www.raspberrypi.org/>`_ (including SD card with OS installed and power supply)
* A `Pibrella <http://pibrella.com/>`_ board
* A USB card reader
* At least one external hard drive (either directly connected to the Pi, or via a USB hub)

Contribute
----------

Patches and pull requests are welcome!
Papou is developed at Github: https://github.com/e2jk/papou


License
-------
Papou is released under the GNU General Public License, version 3 or later.

