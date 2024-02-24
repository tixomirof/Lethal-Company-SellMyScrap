# SellMyScrap
Adds a few terminal commands to sell your scrap from the ship.

This mod aims to sell scrap as close to the target amount as possible. In rare cases, it may exceed the target amount due to performance reasons, even if a suitable match is possible.

* You must be landed at The Company building to use sell commands.
<br><br>
* This mod will NOT sell Gifts, Shotguns, or Ammo by default.
    * See **Sell Settings** for more info.
<br><br>
* This mod has support for excluding custom / modded scrap items from the sell algorithm.
    * See **Advanced Sell Settings** for more info.

## <img src="https://i.imgur.com/TpnrFSH.png" width="20px"> Download

Download [SellMyScrap](https://thunderstore.io/c/lethal-company/p/Zehs/SellMyScrap/) on Thunderstore.

## Terminal Commands
| Command | Description |
| ----------- | ----------- |
| `sell <amount>` | Will sell scrap for a total of the amount specified. Amount is a positive integer. |
| `sell quota` | Will sell scrap to reach the profit quota. |
| `sell all` | Will sell all of your scrap. |

* You must be landed at The Company building to use these commands.
* Each command will sell items based on your config settings.
* Each command requires confirmation before selling your scrap.
    * Additional information is given on the confirmation screen.

| Command |Description |
| ----------- | ----------- |
| `sell` |Will show a help message. |
| `view scrap` | Shows a detailed list of all the scrap in the ship. |
| `view config` | Shows your config settings. |
| `edit config` | Edit config settings in the terminal. |

## Config Settings
If you are experiencing any issues with config settings not working, try deleting the config file and regenerating it by launching the game.<br>
*Reason: Config files from previous versions might have different categories and keys.*

**Sell Settings** and **Advanced Sell Settings** will be synced with the host when joining a lobby.

| Sell Settings | Setting type | Default value | Description |
| ----------- | ----------- | ----------- | ----------- |
| `sellGifts` | `Boolean` | `false` | Do you want to sell Gifts? |
| `sellShotguns` | `Boolean` | `false` | Do you want to sell Shotguns? |
| `sellAmmo` | `Boolean` | `false` | Do you want to sell Ammo? |
| `sellPickles` | `Boolean` | `true` | Do you want to sell Jar of pickles? |

| Advanced Sell Settings | Setting type |Default value | Example value | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| `sellScrapWorthZero` | `Boolean` | `false` |  | Do you want to sell scrap worth zero? |
| `dontSellListJson` | `String` | `[]` | `["Gift", "Shotgun", "Ammo"]` | [JSON array](https://www.w3schools.com/js/js_json_arrays.asp) of item names to not sell. |

* Use the `view-scrap` command or scan in-world to see the correct item names to use.
* Item names are not case-sensitive. Spaces do matter for item names.

| Terminal Settings | Setting type | Default value | Description |
| ----------- | ----------- | ----------- | ----------- |
| `overrideWelcomeMessage` | `Boolean` | `true` | Overrides the terminal welcome message to add some additional info. |
| `overrideHelpMessage` | `Boolean` | `true` | Overrides the terminal help message to add some additional info. |
| `showFoundItems` | `Boolean` | `true` | Show found items on the confirmation screen. |
| `sortFoundItems` | `Boolean` | `true` | Sorts found items from most to least expensive. |
| `alignFoundItemsPrice` | `Boolean` | `true` | Align all prices of found items. |

| Misc Settings | Setting type | Default value | Description |
| ----------- | ----------- | ----------- | ----------- |
| `speakInShip` | `Boolean` | `true` | The Company will speak inside your ship after selling from the terminal. |

## Bug Reports, Help, or Suggestions
https://github.com/ZehsTeam/Lethal-Company-SellMyScrap/issues

| Discord server | Channel | Post |
| ----------- | ----------- | ----------- |
| [Lethal Company modding Discord](https://discord.gg/XeyYqRdRGC) | `#mod-releases` | [SellMyScrap](https://discord.com/channels/1168655651455639582/1197731003800760320) |
| [Unofficial Lethal Company Community](https://discord.gg/nYcQFEpXfU) | `#mod-releases` | [SellMyScrap](https://discord.com/channels/1169792572382773318/1198746789185069177) |

## Screenshots
<div>
    <img src="https://i.imgur.com/ieTZCez.png" width="273px">
    <img src="https://i.imgur.com/atzmgX8.png" width="273px">
    <img src="https://i.imgur.com/4s3oPzD.png" width="273px">
</div>
<h4><code>sell &lt;amount&gt;</code></h4>
<div>
    <img src="https://i.imgur.com/wW6VGUI.png" width="412px">
    <img src="https://i.imgur.com/YvBuyAT.png" width="412px">
</div>
<h4><code>sell quota</code></h4>
<div>
    <img src="https://i.imgur.com/3aE4I8J.png" width="412px">
    <img src="https://i.imgur.com/9rty096.png" width="412px">
</div>
<h4><code>sell all</code></h4>
<div>
    <img src="https://i.imgur.com/XZAcZYO.png" width="412px">
    <img src="https://i.imgur.com/5tcgCKR.png" width="412px">
</div>
<div>
<h4><code>view scrap</code></h4>
<div>
    <img src="https://i.imgur.com/bsfeVpk.png" width="100%">
</div>
<h4><code>view config</code></h4>
<div>
    <img src="https://i.imgur.com/SUDsFt2.png" width="100%">
</div>
