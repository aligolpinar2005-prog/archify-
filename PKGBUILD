# PKGBUILD - archify aracı için
pkgname=archify
pkgver=1.0.0
pkgrel=1
pkgdesc="Her dilden otomatik kaynak kod tarayıp Arch paketi yapan ve AUR'a yükleyen otomasyon aracı."
arch=('any')
url="https://github.com" # Kendi reponuz varsa güncelleyebilirsiniz
license=('GPL')
depends=('python' 'git' 'pacman')

package() {
  # Çalıştırılabilir scripti /usr/bin altına kopyala
  install -Dm755 "$startdir/archify.py" "$pkgdir/usr/bin/archify"
}
