### [ABAP](https://developers.sap.com/topics/abap-platform.html)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/abap.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/abap/archive/master.zip) option and unzip them.

#### Activating theme

1. Close all instances of the SAP Editor and log-off from any connection.
2. Navigate to the SAP GUI theme directory. On Windows: `%APPDATA%\SAP\SAP GUI\ABAP Editor\`
3. Replace `abap_spec.xml` file with the downloaded file with the same name.
(It's advised to copy the original file to another location as a backup.)

#### Customizing theme

To customize, open  abap_spec.xml, and change the nodes inside the COLORSYNTAX tag.

For each TextType node, change either "clr" or "bkclr" properties, using the following internal codes:

- Foreground  = 15923448
- Background
	- Background (read mode) = 3549736
	- Background (edit mode) = 1511953
- CurrentLine = 5916484
- Comment     = 10777186
- Cyan		= 16640395
- Green		= 8125008
- Orange		= 7125247
- Pink		= 13007359
- Purple		= 16356285
- Red			= 5592575
- Yellow		= 9239281