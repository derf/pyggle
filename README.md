pyggle – Python Image Gallery for Static Websites
---

**pyggle** generates a static image gallery with javascript lightbox and a bit
of EXIF data for web hosting. It aims to do one thing well and not do anything
else.

## Demo

See [lib.finalrewind.org](https://lib.finalrewind.org/Wildpark%20Bilsteintal%202020/).

## Usage

There's no proper Python package yet. Clone the git repository and run pyggle
from the directory you want to have the gallery in, while passing it some
image files. I.e.:

```
cd /some/directory
/another/directory/pyggle/bin/pyggle *.jpg
```

pyggle does not support recursion. All images must be located in the current
working directory.
