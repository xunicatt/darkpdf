# darkpdf
A minimal cli tool written in Shell Script to convert normal pdf to dark pdf. darkpdf uses imagemagick to convert pdfs.

# Dependencies
- Imagemagick

Download Imagemagick to use darkpdf:

[Download](https://imagemagick.org/script/download.php)

- Using Brew:
```sh
brew install imagemagick
```

- Using dnf:
```bash
sudo dnf install ImageMagick
```

- Using apt:
```bash
sudo apt install imagemagick
```

# Install
1. Clone the repo.
2. cd into it.
3. Copy the darkpdf script to a directory.
4. Add the directory to $PATH environment variable.

```sh
git clone https://github.com/xunicatt/darkpdf.git
cp -r darkpdf $HOME
chmod u+x $HOME/darkpdf/darkpdf
```

## Add to path:
```sh
#for bash
echo "export PATH=\$PATH:\$HOME/darkpdf" >> ~/.bashrc
source ~/.bashrc

#for zsh
echo "export PATH=\$PATH:\$HOME/darkpdf" >> ~/.zshrc
source ~/.zshrc
```

# Usage
```bash
$ darkpdf hello.pdf
....
$ ls
hello.pdf hello_dark.pdf
```
