2022-06-04 23:35 JST
updated: 2022-07-05 23:44 JST

Please read this README.txt file first, before using this snapshot for x64 architecture.
The ISO image can be used as LiveUSB/DVD or for HDD installation.

User: demo
Demo password: demo
Root password: root

When you are going to install the .iso onto the HDD, please unhold apt-mark as follows. Apt-mark was used to reduce the downloading size up to almost 500 MB of ISO image.

 # apt-mark unhold linux-headers-amd64 linux-image-amd64
 # apt update
 # apt upgrade

** Origin of the "snapshot-20220705_0605.iso"
Modified from a personal respin of
MX-21.1_minimal_x64 Wildflower 18 May 2022
https://sourceforge.net/projects/mx-linux/files/Community_Respins/MX-Minimal/

** Multilingualization (m17n) support
In order to enable Chinese input, click IME toolbar which appears at the right corner on the bottom. Then select item "Chewing". Now you can start Chinese input by pressing Crtl + Space key.
On the other hand, in order to enable Japanese input, click IME toolbar which appears at the same place. Then select item "Anthy". Now you can start Japanese input by pressing Shift + Space key, or alternatively "半/全 漢字" key if your keyboard is Japanese layout.
To return to previous (direct) mode, just press the same key.
If you need another input method for many other languages, add m17n support by installing uim-m17nlib package as follows:
 # apt install uim-m17nlib

** About Universal Input Method (uim)
Uim is an input method module library which supports various scripts and can act as a front end for a range of input methods, including Anthy, Canna, or SKK (for Japanese), Pinyin (for Chinese), Byeoru (for Korean), and M17n (for many other languages). Most of its functions are implemented in Scheme, so it's very simple and flexible.

** Terms of use
See https://mxlinux.org/terms-of-use/
"Anyone distributing a respin that we do not host ourselves must specify that it is a respin in the names of a website, ISO or download location. For example: mx-respin. Furthermore, it must be specified clearly somewhere that products are based on MX Linux but are not connected with it in any official way.
The name "MX Linux" may not be used as part of a respin-project's website title or in the project's iso/media without making clear that the it is not an official part of MX Linux."

This Live ISO image was released in a hope that it would be useful. Therefore you are allowed to redistribute or modify under the GNU General Public License v.3. Its full text can be found both at https://www.gnu.org/licenses/gpl-3.0.html and onboard at /usr/share/common-licenses/GPL-3. But please be noted that the trademark "MX Linux" and its logo exclusively belong to MX Linux Dev Team, which means it is firmly prohibited for commercial usage without permission.

README.txt was created and written
by Green

