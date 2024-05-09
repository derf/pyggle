pyggle – Python Image Gallery for Static Websites
---

**pyggle** generates a static HTML image gallery from filenames passed on the
command line. It aims to do this one thing well and does not support anything
else. Features include:

* chronological sorting of images via EXIF or filesystem timestamps
  (`--sort`, `--reverse`)
* Grouping images by day/month/year
  (`--group`, `--group-files`)
* Reverse geocoding to add place names and OpenStreetMap links to image details
  (`--with-nominatim`, `--nominatim-zoom`)
* Altering images for publication – note that these edit all files in place
  (`--scrub-metadata`, `--resize`, `--exif-copyright`)

**NO MAINTENANCE INTENDED**

pyggle exists to fill a gap in my personal workflow.
It is available as open-source software because why not.
I do not intend to address feature requests or bug reports unless I consider
them interesting or relevant to my personal workflow.

## Demo

See the galleries linked from
[finalrewind.org/pics](https://finalrewind.org/pics/).

## Usage

There is no Python package and thus no installation process.

Clone the git repository and run pyggle from the directory you want to have the
gallery in, while passing it some image files. I.e.:

```
cd /some/directory
/another/directory/pyggle/bin/pyggle *.jpg
```

See `pyggle --help` for a list of options.

All image files must be located in or below the current working directory.
