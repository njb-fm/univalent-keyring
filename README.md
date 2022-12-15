# About なにこれ
GnuPG Keyrings for UVGL.
UVGLのGnuPG鍵でーす。

## How to build a package パッケージの作成方法

#### 1. Import GPG key GPG鍵の導入
```bash
gpg --keyserver keyserver.ubuntu.com --recv-key 048E45A1EC694BCE
```

#### 2. Clone PKGBUILD repository PKGBUILDリポジトリの複製
```bash
git clone https://github.com/FascodeNet/univalent-pkgbuild.git
```

#### 3. Build a package パッケージの作成
```bash
cd univalent-pkgbuild/univalent-keyring
makepkg -s
```

#### Option: Install on your pasocom パソコンに導入する
```bash
sudo pacman -U univalent-keyring-YYYYMMDD-R-any.pkg.tar.zst
```
