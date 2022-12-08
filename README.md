## Introduction

This is the Gelaxy.io team introduction website

## Deploy step by step

### 1. Operating system Prerequisites

Make sure your ubuntu version is 20.04 or later.

```bash
$ cat /etc/issue
Ubuntu 20.04.1 LTS \n \l
```

### 2. Install hugo

```bash
$ sudo apt-get install -y hugo
```

### 3. Clone source code

```bash
$ sudo apt-get install -y git
$ git clone https://github.com/elastos-blockchain/ela-blog-source.git
```

### 4. Run website

```bash
$ cd ela-blog-source
$ sudo hugo server --bind 0.0.0.0 --port 80
Start building sites …
hugo v0.92.2+extended linux/amd64 BuildDate=2022-02-23T16:47:50Z VendorInfo=ubuntu:0.92.2-1

                   | EN
-------------------+-----
  Pages            |  4
  Paginator pages  |  0
  Non-page files   |  0
  Static files     | 72
  Processed images |  0
  Aliases          |  0
  Sitemaps         |  1
  Cleaned          |  0

Built in 24 ms
Watching for changes in ela-blog-source/{archetypes,static,themes}
Watching for config changes in ela-blog-source/config.toml
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at //localhost:80/ (bind address 0.0.0.0)
```
