2023-01-21 12:30 UTC
updated: 08-10 14:20 UTC

Read this readme.txt file first, before using this snapshot for x64 architecture.
The ISO image can be used as Live USB/DVD or for HDD installation.

A snapshot is modified thoroughly from MX-23_CLI_x64 31 July 2023, and applied all latest updates so far.

User: demo
Demo password: demo
Root password: root

** Installation into Hard Disc
In order to install this respin into hard disc, execute the following command from GNOME Terminal as root

 minstall

GNOME Desktop does not support Desktop icons by default, so does installer icon neither.

** Downloading sites
An updated version is usually available at https://sourceforge.net/projects/mx-respin-gnome/
Alternatively, you could download the older releases at a mirror site at https://linux.sakura.ne.jp/mx-respin-iso/ which is mainly for back-ups in case of downtime and might be stored older releases too.

** Origin of this snapshot.iso
Modified from a personal respin of
MX-23_CLI_x64 31 July 2023
https://sourceforge.net/projects/mx-linux/files/Community_Respins/MX-CLI/

** Optional locales (L10n)
The following locales are very well supported (localized):

de_DE.UTF-8 - German locale for Germany
el_GR.UTF-8 - Greek locale for Greece
en_US.UTF-8 - English locale for the USA
es_ES.UTF-8 - Spanish locale for Spain
fr_FR.UTF-8 - French locale for France
hi_IN.UTF-8 - Hindi  locale for India
hr_HR.UTF-8 - Croatian locale for Croatia
hu_HU.UTF-8 - Hungarian locale for Hungary
id_ID.UTF-8 - Indonesian locale for Indonesia
it_IT.UTF-8 - Italian locale for Italy
ja_JP.UTF-8 - Japanese locale for Japan
nl_NL.UTF-8 - Dutch locale for the Netherlands
pl_PL.UTF-8 - Polish locale for Poland
pt_BR.UTF-8 - Portuguese locale for Brasil
ru_RU.UTF-8 - Russian locale for Russia
sv_SE.UTF-8 - Swedish locale for Sweden
zh_CN.UTF-8 - Chinese locale for Simplified Chinese (簡体字)
zh_TW.UTF-8 - Chinese locale for Traditional Chinese (繁体字)

Note:
gnome-xxxxxxxx.iso ----- Default language (locale) is NOT set. You should choose from among pull-down list.

You can choose whatever locale you want to use at Boot Menu Option. And also, to change another locale after system booting, logout a present desktop session. Then, click on the upper right corner on the login screen, and choose a locale from a drop-down list. Simply logout and then login again can change a locale for a desktop session.

** Multilingualization (m17n) support
By default, it support direct input.
In order to enable Japanese input, for example, click IME toolbar which appears at the right corner on the top. Then select item "Anthy". Now you can start Japanese input by pressing Crtl + J key.

by pressing Crtl + J key again returns to Direct mode.

If you need another input method for many other languages, add ibus-**** package as follows:
 # apt install ibus-chewing

** About Intelligent Input Bus (Ibus)
Ibus is an input method module library which supports various scripts and can act as a front end for a range of input methods, including Anthy, Canna, or SKK (for Japanese), Pinyin (for Chinese), Byeoru (for Korean), and M17n (for many other languages). Most of its functions are implemented in Scheme, so it's very simple and flexible.

By default, Ibus toolbar appears on the system tray.

** Terms of use
See https://mxlinux.org/terms-of-use/
"Anyone distributing a respin that we do not host ourselves must specify that it is a respin in the names of a website, ISO or download location. For example: mx-respin. Furthermore, it must be specified clearly somewhere that products are based on MX Linux but are not connected with it in any official way.
The name "MX Linux" may not be used as part of a respin-project's website title or in the project's iso/media without making clear that the it is not an official part of MX Linux."

This Live ISO image was released in a hope that it would be useful. Therefore you are allowed to redistribute or modify under the GNU General Public License v.3. Its full text can be found both at https://www.gnu.org/licenses/gpl-3.0.html and onboard at /usr/share/common-licenses/GPL-3. But please be noted that the trademark "MX Linux" and its logo exclusively belong to MX Linux Dev Team, which means it is firmly prohibited for commercial usage without permission.

README.txt was created and written
by Green

