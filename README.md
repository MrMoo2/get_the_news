##### Get the papers front pages (download_news) 1.1

Will loop through the URLs listed in the (file_to_read) and retrieve the images of today's news paper front pages and then smoosh them into one image (jpg) for my desktop image. 

Every time it runs it backs up the current ones before getting the new ones, so watch it getting to big!

It relies on having imagemagick installed and is very much geared up for the website img.kiosko.net. *All the configuration is hard coded in the top of the script, so change that before running.*

The URL list (file_to_read) can cope with simple replacement values...

```
    [DATE]                  :   2025/06/24
    [YEAR]                  :   2025
    [MONTH]                 :   06
    [DAY]                   :   24
    [DATE_NO_SEPARATORS]    :   20250624
```

Each entry must start with 'http'.

###### Usage

```
./download_news [OPTION]
```

Options are...

Very limited and are mainly just hard coded at the top of the script.

```

    -d  Override today's a date to use...
        $0 -d 2025-06-24
```

###### TODO
    7 Build a better one in a better language with more configuration.
    9 Error checking for manually entered dates and no file.

Feel free to do with this as you please, but I take no responsibility for its use or functionality. That said...

Any bugs or pointers... <script@rubbermonkeys.co.uk>.
