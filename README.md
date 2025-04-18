# svg cursors on linux

Currently there are 2 different implementations of svg based cursors on linux, neither a standard yet and AFAIK they are not interoperable. <br />
If you know of any more themes for either implementation please open a pr/issue!

| name/original | hyprcursor - 2024.03. | plasma - 2024.10. |
| --- | --- | --- |
| [Apple Cursor](https://github.com/ful1e5/apple_cursor) | https://github.com/driedpampas/macOS-hyprcursor ||
| [Bibata](https://github.com/ful1e5/Bibata_Cursor) | https://github.com/LOSEARDES77/Bibata-Cursor-hyprcursor/ , aslo has built in support||
| [Breeze](https://invent.kde.org/plasma/breeze/-/tree/master/cursors) || https://invent.kde.org/plasma/breeze/-/tree/master/cursors/Breeze/Breeze/cursors_scalable, https://invent.kde.org/plasma/breeze/-/tree/master/cursors/Breeze_Light/Breeze_Light/cursors_scalable |
| [BreezeX](https://github.com/ful1e5/BreezeX_Cursor) | has built in support ||
| [Catppuccin](https://github.com/catppuccin/cursors) | https://github.com/entailz/HyprcatoSVG/blob/master/README.md , also has built in support ||
| [DeepinV20 White Cursors](https://github.com/yeyushengfan258/DeepinV20-white-cursors) | https://github.com/PaideiaDilemma/DeepinV20-white-cursors ||
| [Dracula KDE](https://github.com/dracula/gtk/tree/master/kde/cursors) | https://github.com/guillaumeboehm/hyprcursor_dracula_kde ||
| [Future](https://github.com/yeyushengfan258/Future-cursors) | https://gitlab.com/Pummelfisch/future-cyan-hyprcursor - cyan ||
| [McMojave](https://github.com/vinceliuice/McMojave-cursors) | https://github.com/Libadoxon/mcmojave-hyprcursor, https://github.com/OtaK/McMojave-hyprcursor | |
| [Nordzy](https://github.com/alvatip/Nordzy-cursors) | https://github.com/guillaumeboehm/Nordzy-hyprcursors ||
| [Notwaita](https://gitlab.com/donut2/notwaita-cursor-theme) | https://github.com/ful1e5/notwaita-cursor - black, white and gray||
| [Phinger](https://github.com/phisch/phinger-cursors) | https://github.com/Jappie3/hyprcursor-phinger ||
| [Posy's Cursor](https://www.michieldb.nl/other/cursors/) | https://github.com/Morxemplum/posys-cursor-scalable - white, black, mono, and mono black ||
| [Qogir](https://github.com/vinceliuice/Qogir-icon-theme) | | has built in support |
| [Rosé Pine](https://github.com/rose-pine/cursor?tab=readme-ov-file) | https://github.com/ndom91/rose-pine-hyprcursor ||
| [Vimix](https://github.com/vinceliuice/Vimix-cursors) | https://github.com/BlackFuffey/vimix-hyprcursor ||
| [Xcursor-Pro](https://github.com/ful1e5/XCursor-pro) | https://github.com/4lrick/XCursor-Pro-Hyprcursor - dark, light, red ||

| name/original | available on the hyprland discord server as compressed binaries |
| --- | --- |
| [Bibata](https://github.com/ful1e5/Bibata_Cursor) | HyprBibataModernClassicSVG.tar.gz |
| [BreezeX](https://github.com/ful1e5/BreezeX_Cursor) | BreezeX-Dark-hyprcursor.zip, BreezeX-Amber.zip |
| [Capitaine](https://github.com/keeferrourke/capitaine-cursors) | HyprCapitaineSVG.tar.gz, Capitaine_Gruvbox_Dark.zip |
| [Catppuccin](https://github.com/catppuccin/cursors) | HyprcursorCatppuccinMochaMauve.tar.gz |
| [GoogleDot](https://github.com/ful1e5/Google_Cursor) | GoogleDot-Black.zip, extracted_GoogleDot-Violet-SVG.zip, GoogleDot-Blue-Hyprcursor.tar.gz |
| [Material](https://github.com/varlesh/material-cursors) | material-cursors.tar.gz, material-dark-cursors.tar.gz, material-light-cursors.tar.gz |
| [Nordzy](https://github.com/alvatip/Nordzy-cursors) | Nordzy-cursors-white-HYPR.tar.gz |
| [Phinger](https://github.com/phisch/phinger-cursors) | phinger-hyprcursors-light.tar.gz - light |
| [Posy's](https://github.com/simtrami/posy-improved-cursor-linux) | hypr_posycursor.tar.gz, Posy_Cursor_Black_h.tar.gz |
| [Qogir](https://github.com/vinceliuice/Qogir-icon-theme) | qogir_hl.tar.gz |
| [Rosé Pine](https://github.com/rose-pine/cursor?tab=readme-ov-file) | rose-pine-cursor-hyprcursor.tar.gz |
| [Sonic](http://www.rw-designer.com/cursor-set/sonic-v64) | Sonic-cursor-hyprcursor.tar |
| [Spore](https://en.wikipedia.org/wiki/Spore_(2008_video_game)) | Spore-hyprcursor-theme.tar.gz |
| [Tachy](https://www.pixiv.net/en/artworks/91387058) | hyprTachy.7z |
| [Volantes](https://github.com/varlesh/volantes-cursors) | volantes.tar.gz |

# Blogs, articles and more on svg cursors

### wayland <br />
https://wayland.app/protocols/cursor-shape-v1 - the protocol making svg cursors viable <br />

### hyprcursor <br />
https://github.com/ATM-Jahid/accurse - compile cursor themes from svg files into xcursor and hypercursor themes <br />
https://wiki.hyprland.org/Hypr-Ecosystem/hyprcursor/ <br />
https://blog.vaxry.net/articles/2024-cursors <br />
https://standards.hyprland.org/hyprcursor/ <br />
https://github.com/hyprwm/hyprcursor <br />

### kde plasma <br />
https://blogs.kde.org/2025/01/12/kcursorgen-and-svg-cursors/ <br />
https://planet.kde.org/vlad-zahorodnii-2024-10-06-svg-cursors-everything-that-you-need-to-know-about-them/ <br />
https://blogs.kde.org/2024/10/09/cursor-size-problems-in-wayland-explained/ <br />
https://invent.kde.org/plasma/breeze/-/merge_requests/433 - this would've been hyprcursor on kde (closed) <br />
https://invent.kde.org/plasma/breeze/-/merge_requests/475 (merged) <br />
https://invent.kde.org/plasma/kwin/-/merge_requests/6187 (merged) <br />

I have seen 1 similar list: https://github.com/sakshatshinde/hyprcursor-themes

I collected the list based on hyprlands discord server room [#hyprcursor-themes](https://discord.com/channels/961691461554950145/1216066899729977435)
For the plasma talk check out: https://webchat.kde.org/#/room/#kwin:kde.org, or their mailing [list](https://mail.kde.org/mailman/listinfo/kwin)!
