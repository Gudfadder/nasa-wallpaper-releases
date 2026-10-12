# NASA Wallpaper Releases

Official release downloads for NASA Wallpaper.
NASA Wallpaper is a desktop application that automatically finds and applies high-resolution space imagery from NASA's Image and Video Library as your wallpaper.

## Features

- **Automatic daily wallpaper rotation**  
  Automatically changes your wallpaper once per day using NASA imagery that matches your selected filters. On Linux, this is handled through a user-level systemd timer.

- **Manual "Next Wallpaper" function**  
  Change to the next valid NASA wallpaper at any time without waiting for the automatic daily rotation.

- **NASA image filtering by subject**  
  Choose which types of space imagery should be included in the wallpaper pool, such as nebulae, galaxies, planets, moons, and auroras.

- **Minimum photo year filtering**  
  Set the oldest year you want to allow when searching NASA's image library. This makes it possible to focus on newer imagery or include older archival material. Default is 1946.

- **Multiple image quality modes**  
  Choose how strict the application should be when accepting images. Higher quality modes require larger images that better match modern desktop resolutions, while more permissive modes allow a broader range of NASA imagery. Historic recommended if you want older photos.

- **Multi-monitor wallpaper handling**  
  Detects connected displays and creates a single wallpaper canvas that matches the full desktop layout across multiple monitors.

- **Per-monitor display modes**  
  Each connected monitor can independently use either a fill-style crop or the image's original aspect and size, allowing different display preferences for different screens.

- **Offline wallpaper library creation support**  
  Pre-download wallpapers that match your current filters so the application can continue rotating wallpapers without needing to contact NASA each time.

- **Local wallpaper history and maintenance tools**  
  Keeps track of previously used wallpapers to avoid immediate repetition, and includes maintenance controls for clearing wallpaper history or removing downloaded images.

## Current Release

Version 1.0.0

### Linux

Debian/Ubuntu package: `nasa-wallpaper_1.0.0_all.deb`

Windows releases will be added later.