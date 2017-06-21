Name
----
gpo-zugaina-downloader - Download overlay, category or package ebuilds from gpo.zugaina.org

Synopsis
--------
gpo-zugaina-downloader [OPTIONS] PREFIX OVERLAY [CATEGORY_PACKAGE]

Parameters
----------
    PREFIX               destination of downloaded files
    OVERLAY              name of overlay
    CATEGORY_PACKAGE     category or category/package that you want download

Options
-------
    -v, --verbose   tree print of downloaded files
    -p, --pretend   display what will downloaded
    -h, --help      display this help and exit

Examples
--------
    gpo-zugaina-downloader my_prefix_dir kde                      ->  for download all ebuilds from kde overlay
    gpo-zugaina-downloader my_prefix_dir kde kde-misc             ->  for download kde-misc category ebuilds from kde overlay
    gpo-zugaina-downloader my_prefix_dir kde kde-misc/kdeconnect  ->  for download all kdeconnect package ebuilds from kde overlay
