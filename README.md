# A ROS-O deb repository for noble-one-unstable

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/cjue/ros-o-builder/blob/noble-one-unstable/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/cjue/ros-o-builder/noble-one-unstable/repository/ ./" | sudo tee /etc/apt/sources.list.d/cjue_ros-o-builder-noble-one-unstable.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/cjue/ros-o-builder/noble-one-unstable/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-cjue_ros-o-builder-noble-one-unstable.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | noble-one |
| Architecture |  |
| Available Packages | 0 |
| Build Date | Tue Jan 13 09:58:32 UTC 2026 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="setup_files" href="#setup_files">:construction:</a> | [:green_book:](https://raw.githubusercontent.com/cjue/ros-o-builder/noble-one-unstable/repository/setup_files_0-2026.01.13.09.38-bloom_generate.log) [:orange_book:](https://raw.githubusercontent.com/cjue/ros-o-builder/noble-one-unstable/repository/ros-one-setup-files_0-2026.01.13.09.38_amd64-2026-01-13T09:38:09Z.build) | setup_files | 0-2026.01.13.09.38 |  | [:link:](https://github.com/v4hn/setup_files/tree/main) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="setup_files" href="#setup_files">:construction:</a> | [:green_book:](https://raw.githubusercontent.com/cjue/ros-o-builder/noble-one-unstable/repository/setup_files_0-2026.01.13.09.38-bloom_generate.log) [:orange_book:](https://raw.githubusercontent.com/cjue/ros-o-builder/noble-one-unstable/repository/ros-one-setup-files_0-2026.01.13.09.38_amd64-2026-01-13T09:38:09Z.build) | setup_files | 0-2026.01.13.09.38 |  | [:link:](https://github.com/v4hn/setup_files/tree/main) |
