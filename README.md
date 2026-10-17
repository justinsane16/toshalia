# Toshalia

Toshalia is a minimap overlay for the game [Palia](https://palia.com). It is a free fan project. It is not made,
approved or supported by Singularity 6.

Download the installers only from the [Releases](../../releases) page of this repository.

## Editions

Players have different ideas of what is fair. So Toshalia comes in three editions. Each edition contains only the
code of its own features. The Minimap edition cannot read fish or resources, because that code is not in it.

| Edition | What it shows |
|---|---|
| **Minimap** | A minimap of the zone, with your position, the camera direction, villagers, stable boards and your party members. |
| **Minimap + Fishing** | All of the Minimap edition. Also the fish on your hook as soon as it bites, the fish of your party members and of players near you, and an optional block of the left click for rare fish. |
| **Full** | All of the Fishing edition. Also the resources near you on the minimap: ore, trees, forageables, bugs and hunting creatures, with Infected, Amber and star quality marks. |

## Requirements

- Windows 10 or Windows 11 (64-bit).
- Palia in **Windowed** or **Windowed Fullscreen** mode. An overlay cannot show over exclusive fullscreen.
- The Steam client of Palia or the client from palia.com.

## Install, change edition, uninstall

1. Download the installer of the edition that you want, for example `Toshalia Minimap Setup 0.1.0.exe`.
2. Run it. It installs for your Windows user only and does not ask for administrator rights. It makes a "Toshalia"
   shortcut on the desktop and in the Start menu, and starts Toshalia.
3. To change edition, run the installer of the other edition. It replaces the installed edition and keeps your
   settings.
4. To uninstall, use **Settings > Apps > Installed apps > Toshalia**. The uninstaller asks if it must also delete
   your settings. If you choose No, they stay in `%APPDATA%\Toshalia` for a later install.

The installers are not code-signed yet. Windows can show "Windows protected your PC". To install, click
"More info", then "Run anyway".

## Check your download

Each release has a `SHA256SUMS.txt` file. In PowerShell, run:

```powershell
Get-FileHash "Toshalia Minimap Setup 0.1.0.exe" -Algorithm SHA256
```

The hash must be the same as the hash in `SHA256SUMS.txt`. If it is not the same, do not run the file.

## Risks

- Toshalia reads the memory of the game. It only reads. It does not change the game or send anything to the game.
- Third-party tools can be against the terms of service of Palia. Use Toshalia at your own risk. The author is not
  responsible for actions against your account.
- A game update can stop Toshalia from working. Toshalia then tells you to look for a new version.

## Privacy

- Toshalia does not connect to the internet. It sends no data anywhere.
- It keeps your settings and a log file on your PC, in `%APPDATA%\Toshalia`. The log does not contain your Windows
  user name or the names of other players.

## Help and new versions

Toshalia does not check for updates. New versions and help are on the Discord server: https://discord.gg/yVuTdkwq9v

When you report a problem, tell us your edition and your Palia client (Steam or palia.com), and attach the log file
`%APPDATA%\Toshalia\logs\main.log`.

## Licence

See [LICENSE.txt](LICENSE.txt). Palia and its art are the property of Singularity 6.
