# Bookworm

___A focused eBook reader___

Read the books you love without having to worry about the different format complexities like EPUB, PDF, MOBI, CBR, etc.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub com.github.babluboy.bookworm
flatpak run com.github.babluboy.bookworm
```

## Building

```bash
git clone git@github.com:flathub/com.github.babluboy.bookworm.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.github.babluboy.bookworm.yaml
```
