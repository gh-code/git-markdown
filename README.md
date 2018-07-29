# git-markdown
Git deployment for Markdown to HTML. [markdown-styles](https://github.com/mixu/markdown-styles) is adopted.

## Usage

### 1. Already have deployment directory
``/home/`whoami`/public_html/markdown``

### 2. Server Side
```
git clone https://github.com/gh-code/git-markdown.git
cd git-markdown/bin
./git-markdown website /home/`whoami`/public_html/markdown
```

### 3. Local Side
```
mkdir ~/website
cd ~/website
git init
echo -e "# Title\n## Title 2" > index.md
git add index.md
git commit -m "Initial commit"
git remote add origin me@server:repo/website.git
git push origin master
```

## License
MIT License
