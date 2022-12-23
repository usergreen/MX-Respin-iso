2022-12-22 20:20 JST
updated: ------- JST

Read this README.txt file first, before using this snapshot for x64 architecture.
The ISO image can be used as Live USB/DVD or for HDD installation.

This unofficial snapshot provides Budgie Deesktop environment, and modified from MX-21.1_minimal_x64 Wildflower 18 May 2022.
As for this re-spin, it is labeled "mx-respin-iso-21.2.1_x64, December 22, 2022 (bullseye-11.6)", as shown at the boot menu.

User: demo
Demo password: demo
Root password: root

** Known bug
In order to change a background (wallpaper) or add a new one on Desktop, please set it from Main Menu > Preferences > Tweaks > Appearance > Background > image. At present, changing a wallpaper should need a help of GNOME Tweaks (You can NOT add wallpaper from System Settings > Background). 

** Downloading sites
An updated version is usually available at https://sourceforge.net/projects/mx-respin-iso/
Alternatively, you could download the same file at a mirror site at https://linux.sakura.ne.jp/mx-respin-iso/ which is mainly for back-ups in case of downtime and might be stored older releases too.

** Origin of this snapshot.iso
Modified from a personal respin of
MX-21.1_minimal_x64 Wildflower 18 May 2022
https://sourceforge.net/projects/mx-linux/files/Community_Respins/MX-Minimal/

** Default localization (L10n)
Supported default options are:
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
pt_BR.UTF-8 - Portuguese locale for Brasil
ru_RU.UTF-8 - Russian locale for Russia
sv_SE.UTF-8 - Swedish locale for Sweden
zh_CN.UTF-8 - Chinese locale for China (簡体字)
zh_TW.UTF-8 - Chinese locale for China (繁体字)

Note:
No default language (locale) is set; that is "C" for English.
To change another locale after system booting, logout a present desktop session. Then, click on the upper right corner on the login screen, and choose a locale from a drop-down list. Simply logout and then login again can change a locale for a desktop session.

** Multilingualization (m17n) support
In order to enable Chinese input, click IME toolbar which appears at the right corner on the bottom. Then select item "Chewing". Now you can start Chinese input by pressing Crtl + Space key.
On the other hand, in order to enable Japanese input, click IME toolbar which appears at the same place. Then select item "Anthy". Now you can start Japanese input by pressing Shift + Space key, or alternatively "半/全 漢字" key if your keyboard is Japanese layout.
To return to previous (direct) mode, just press the same key.
If you need another input method for many other languages, add m17n support by installing uim-m17nlib package as follows:
 # apt install uim-m17nlib

** About Universal Input Method (uim)
Uim is an input method module library which supports various scripts and can act as a front end for a range of input methods, including Anthy, Canna, or SKK (for Japanese), Pinyin (for Chinese), Byeoru (for Korean), and M17n (for many other languages). Most of its functions are implemented in Scheme, so it's very simple and flexible.

If you want to use UimToolbar utilities, which shows and controls uim mode, for system tray, add the following, too.

 $ uim-toolbar-gtk3-systray &

** Terms of use
See https://mxlinux.org/terms-of-use/
"Anyone distributing a respin that we do not host ourselves must specify that it is a respin in the names of a website, ISO or download location. For example: mx-respin. Furthermore, it must be specified clearly somewhere that products are based on MX Linux but are not connected with it in any official way.
The name "MX Linux" may not be used as part of a respin-project's website title or in the project's iso/media without making clear that the it is not an official part of MX Linux."

This Live ISO image was released in a hope that it would be useful. Therefore you are allowed to redistribute or modify under the GNU General Public License v.3. Its full text can be found both at https://www.gnu.org/licenses/gpl-3.0.html and onboard at /usr/share/common-licenses/GPL-3. But please be noted that the trademark "MX Linux" and its logo exclusively belong to MX Linux Dev Team, which means it is firmly prohibited for commercial usage without permission.

README.txt was created and written
by Green

