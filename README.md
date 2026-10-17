# Toshalia

Toshalia is a minimap overlay for the game [Palia](https://palia.com). It is a free fan project. It is not made,
approved or supported by Singularity 6.

Download the installers only from the [Releases](../../releases) page of this repository.

|---|---|
| **Minimap** | A minimap of the zone, with your position, the camera direction, villagers, stable boards and your party members. |
| **Minimap + Fishing** | All of the Minimap edition. Also the fish on your hook as soon as the bobber lands in the water, the fish of your party members and of players near you.|
| **Full** | All of the Fishing edition. Also the resources near you on the minimap: ore, trees, forageables, bugs and hunting creatures, with Infected, Amber and star quality marks. |

## Requirements

- Windows 10 or Windows 11 (64-bit).
- Palia in **Windowed** or **Windowed Fullscreen** mode. An overlay cannot show over exclusive fullscreen.
- The Steam client of Palia or the client from palia.com.

## Check out the discord server for instructions and important information before downloading
- [https://discord.com/yVuTdkwq9v](https://discord.gg/yVuTdkwq9v)

## Check your download

Each release has a `SHA256SUMS.txt` file. In PowerShell, run:

```powershell
Get-FileHash "Toshalia Minimap Setup 0.1.0.exe" -Algorithm SHA256
```

The hash must be the same as the hash in `SHA256SUMS.txt`. If it is not the same, do not run the file.

## Risks

- Toshalia reads the memory of the game. It only reads. It does not change the game or send anything to the game.
- Third-party tools are against the terms of service of Palia. Use Toshalia at your own risk. The author is not
  responsible for actions against your account.
- A game update can stop Toshalia from working. Toshalia then tells you to look for a new version.

## Privacy

- Toshalia does not connect to the internet. It sends no data anywhere.
- It keeps your settings and a log file on your PC, in `%APPDATA%\Toshalia`. The log does not contain your Windows
  user name or the names of other players.

## Help and new versions

Toshalia does not check for updates. New versions and help are on the Discord server: [https://discord.gg/yVuTdkwq9v](https://discord.gg/yVuTdkwq9v)


## Licence

See [LICENSE.txt](LICENSE.txt). Palia and its art are the property of Singularity 6.
