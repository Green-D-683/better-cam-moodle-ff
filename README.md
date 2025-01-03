<p align="center">
  <img src="https://raw.githubusercontent.com/lakeesiv/better-cam-moodle/master/img/logo1.png" width="150" 
  />
</p>

> Trash logo ik but I'm too lazy to make a better one

# Better Cam Moodle

## Installation

Due to Firefox Policy, the addon is not able to be listed publicly on the firefox store, but can be installed through the following link:

- [https://addons.mozilla.org/firefox/downloads/file/4411599/better_cam_moodle-1.0.2.0.xpi](https://addons.mozilla.org/firefox/downloads/file/4411599/better_cam_moodle-1.0.2.0.xpi)

## Description

Since the introduction of Moodle 4.0, the UI for moodle is not as good as it used to be. There are

- Unnecessary card images which take up a lot of space
- Everything is **way too big**
- Inconsistent UI (especially with spacing)
- Sidebar which cannot be hidden

This theme aims to fix all of these issues and make moodle look better. It gives you many options to customize how you want moodle to look like. It also enables auto login!

## Before

![](img/home-before.png)
![](img/course-before.png)

## After

![](img/home-after.png)
![](img/course-after.png)

## Features

### Remove Course Sidebar

|       With Sidebar        |          Without          |
| :-----------------------: | :-----------------------: |
| ![](img/with-sidebar.png) | ![](img/course-after.png) |

### Remove Dashboard Right Block

|        With Rightblock        |         Without         |
| :---------------------------: | :---------------------: |
| ![](img/with-right-block.png) | ![](img/home-after.png) |

### Remove Useless Links

Just remove the useless links at the nav, keeping only the `Dashboard` and `Courses` and `Course History` links.

![Useless Links](img/with-useless-links.png)
With Useless Links

### Remove Edit Mode

Remove the edit mode button at the top right corner.

![Edit Mode](img/with-edit-mode.png)

### Auto Login

Automatically login to moodle when you visit the site. No more clicking on the login using Raven button!

### Cleanup Right Block

This will remove all the useless links in the right block of the dashboard, so you will se the panopto links first, preventing you from having to scroll down to see them.

# Development

Install the dependencies

```bash
pnpm install
```

Run the dev server

```bash
pnpm dev
```

Open the `src` directory in Chrome extensions and load the unpacked extension.

To build the extension, run

```bash
pnpm build
```

You can then load the extension from the `dist` directory.

# License

MIT
