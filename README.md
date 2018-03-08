# Desktop Folder
Bring your desktop back to life.
This is a fork of [Desktop Folder](https://github.com/spheras/desktopfolder), focusing on a more traditional desktop experience.

![Desktop Folder Banner](https://raw.githubusercontent.com/spheras/desktopfolder/master/etc/banner.png)

## Description
Organize your desktop with panels that hold your things.
- Desktop folder is open by default, panels are optional.
- Access files, folders and apps from your desktop
- Drop files, folders, links and .desktop launchers inside panels
- Resize, position and color panels
- Reveal the desktop with ⌘-D

## Contributing

See the [Contributing page](https://github.com/spheras/desktopfolder/wiki/Contributing) on the wiki.

## Building and Installing
You'll need the following dependencies to build:

* libgee-0.8-dev
* libcairo2-dev
* libjson-glib-dev
* libgdk-pixbuf2.0-dev
* libwnck-3-dev
* libgtksourceview-3.0-dev
* libjson-glib-dev
* meson
* valac

Run `meson build` to configure the build environment and then change to the build directory and run `ninja` to build:

    meson build
    cd build
    meson configure -D prefix=/usr
    ninja

To install, use `ninja install`, then execute with `com.github.spheras.desktopfolder`:

    sudo ninja install
    com.github.spheras.desktopfolder
