# WordPress.org listing assets

Published to SVN's `assets/` directory by the deploy workflow, not shipped
inside the plugin. Names are fixed by the plugin directory:

| File | Size | What it is |
| --- | --- | --- |
| `icon-256x256.png` | 256x256 | The icon in search results and the plugin card. |
| `banner-772x250.png` | 772x250 | The header on the plugin page. |
| `banner-1544x500.png` | 1544x500 | The same banner for retina displays. |
| `screenshot-1.png` … | any, shown at 772 wide | In the order readme.txt's `== Screenshots ==` captions them. |

The captions live in `readme.txt` and are matched by position, so a screenshot
added or reordered here has to move there too, or every caption after it
describes the wrong image.
