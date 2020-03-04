#Maintainer: Sanskrit Coders <sanskrit-programmers@googlegroups.com>
pkgname=dyuganga
pkgver=1.1
pkgrel=1
pkgdesc="A dummy package which pulls some software useful for sanskrit/ saMskRtam / संस्कृतम् users. Curated by the dyuganga team - https://sanskrit.github.io/groups/dyuganga/ ."
url="http://github.com/sanskrit-coders/dyuganga-aur"
# license=('custom:OFL')
arch=(any)

depends=(
'redshift'
# Browsing
'firefox'
# Editing and publishing
'sanskrit-fonts'
'atom'
'hugo'
'git'
# IME
'fcitx'
'fcitx-m17n'
'fcitx-gtk2'
'fcitx-gtk3'
'fcitx-qt4'
'fcitx-qt5'
'm17n-db-indic'
'autokey'
'parcellite'
# Data
'stardict-indic-update'
# Image editing
'gimp'
# Video editing
'peek'
# Audio editing
'vlc'
'audacity'
'easytag'
'soundconverter'
# Communication
'telegram-desktop'
'zoom'
# File sharing
'nemo-dropbox'
)

optdepends=(
'obs-studio'
'obs-qtwebkit-git'
'obs-gphoto'
'intellij-idea-ce'
'intellij-idea-ultimate-edition'
'stellarium'
'skychart-bin'
'geogebra'
)

package() {
  install -d "$pkgdir/etc/profile.d/"
  wget --output-document "$pkgdir/etc/profile.d/ime.sh" https://raw.githubusercontent.com/sanskrit-coders/dyuganga-aur/master/ime.sh
}