## openplotter-settings

Main OpenPlotter app

### Installing

#### For production

Download and install the latest .deb file from [![Latest version of 'openplotter-settings' @ Cloudsmith](https://api-prd.cloudsmith.io/v1/badges/version/openplotter/openplotter/deb/openplotter-settings/latest/a=all;d=debian%252Fbullseye;t=binary/?render=true&show_latest=true)](https://cloudsmith.io/~openplotter/repos/openplotter/packages/detail/deb/openplotter-settings/latest/a=all;d=debian%252Fbullseye;t=binary/)

`sudo apt-get install ./openplotter-settings_*.*.*-*_all.deb`

#### For development

Clone the repository:

`git clone https://github.com/openplotter/openplotter-settings.git`

Make your changes and create the package:

```
cd openplotter-settings
dpkg-buildpackage -b
```
Install the package:

```
cd ..
sudo apt-get ./openplotter-settings_x.x.x-xxx_all.deb
```

Run:

`openplotter-settings`

Pull request your changes to github and we will check and add them to the next version of the [Debian package](https://cloudsmith.io/~openplotter/repos/openplotter/packages/).

### Documentation

https://openplotter.readthedocs.io

### Support

http://forum.openmarine.net/forumdisplay.php?fid=1
