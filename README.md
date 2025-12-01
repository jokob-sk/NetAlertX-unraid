# NetAlertX - Unraid

## NetAlertX Unraid XML template

### Setup

Firstly you need to be running unRAID ver 6.0.0 or later, once installed follow the instructions below:

#### NOTE

1. Make folders and set permissions:

   - `mkdir -p /mnt/user/appdata/netalertx`
   - `chown -R 20211:20211 /mnt/user/appdata/netalertx`
   - `chmod -R 755 /mnt/user/appdata/netalertx`

2. Install NetAlertX App:
   - Install Community Applications Plugin.
   - Search for NetAlertX by masterwishx and install it.
   - Once the image is downloaded you should see it appear in the "Docker Containers" sub-tab.

3. Enjoy

### Warning

*Using tmpfs reduces disk writes and speeds up I/O, but all data stored in memory will be lost on restart.
If you need to keep a persistent, file-based log history, add* **Log Path** *to the container:*

   `/mnt/user/appdata/netalertx/log:/tmp/log`

- Full credit for the initial release goes to [masterwishx](https://github.com/masterwishx/unraid-templates).
- [NetAlertX.xml](https://github.com/masterwishx/unraid-templates/blob/main/NetAlertX.xml)
- [Unraid Support](https://forums.unraid.net/topic/195448-support-template-masterwishx-netalertx)
