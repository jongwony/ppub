# ppub

Local image packaging.

your project image directory connected with default screen shot directory.

## Setup

```
mkdir -p ~/bin && cp ppub $_
chmod +x ~/bin/ppub
export PATH=$HOME/bin:$PATH
```

## Usage

Markdown image file example

*Rendering file must be staged at least*

```
# cmd + shift + 3 or 4 [take screen shot default directory]
# cmd + c in finder
![alt](<PASTE>)
```

```
cd <GIT PROJECT>
ppub
```

[![asciicast](https://asciinema.org/a/UHv5eLtSDZu9hOJsbsBEMAph8.png)](https://asciinema.org/a/UHv5eLtSDZu9hOJsbsBEMAph8)
