# itchio-bottles-setup
This script sets up a custom wine executable that itch.io uses to start Windows 
games in a prefix created with Bottles.

> **!NOTE!**: This script need Bottles 2022.5.28-3 or greater to work.

## Installation
### Using `curl`
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/mirkobrombin/itchio-bottles-setup/main/itchio-bottles-setup)"
```

### Using `wget`
```bash
sh -c "$(wget https://raw.githubusercontent.com/mirkobrombin/itchio-bottles-setup/main/itchio-bottles-setup -O -)"
```

## Tweaking
The script can be tweaked to behave differently depending on your needs.

Once the script is downloaded, open it in your text editor (e.g. nano) and
look for the **Settings** section.

| **Setting** | **Value** |
| ------------ | --------- |
| `_ITCH_DESKTOP_PATH` | The path to the itch.io desktop entry. |
| `_WINE_SCRIPT_PATH` | Where the wine script will be placed. |

You can also tweak the script to add more options to the wine script; look
for the **Samples** section.
