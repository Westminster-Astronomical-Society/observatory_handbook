# NexStar Controller Reference

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/NexStar.png
---
name: nexstar-controller
---
NexStar controller
```

:::
:::{grid-item}

1. **LCD**: Dual-line, 16 character display.

2. **Align**: Use a selected star or object as an alignment position.

3. **Direction keys**: Slew the telescope in RA and Dec for alignment or centering objects.

4. **Catalog keys**: Direct access to each of the database catalogs. See catalog lists below.

5. **Info**: Coordinates and selected object information.

6. **Tour**: Tour of the best objects for the current date and time.

7. **Enter**: Select any of the telescope's functions and accept entered parameters.

8. **Undo**: Display the previous level in the menu or erase data entered by mistake.

9. **Menu**: Display setup and utilities functions.

10. **Scroll keys**: Scroll up and down within any of the menu lists.

11. **Rate**: With #1-9 Changes the manual slew rate for the direction buttons.

12. **RS-232 jack**: Computer interface and remote control of the telescope.
:::
::::

## Controller menus

### `ALIGN`

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu_align.svg
---
name: nexstar-menu-align
---
NexStar Align Menu
```

:::
:::{grid-item}

- **`ALIGNMENT STARS`:** Update original alignment with new alignment stars.

- **`CALIB. STARS`:** Add or update additional calibration stars.

- **`POLAR ALIGN`:** Perform "All-Star" polar alignment and view polar alignment error.

- **`SYNC`:** Sync the mount's coordinates to the given equatorial coordinates.

- **`UNDO SYNC`:** Undo the sync (required when realigning the mount).

:::
::::

### `MENU`

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu.svg
---
name: nexstar-menu
---
NexStar Menu
```

:::
:::{grid-item}


:::
::::

#### `TRACKING`

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu_tracking.svg
---
name: nexstar-menu-tracking
---
NexStar Menu - Tracking
```

:::
:::{grid-item}

- **`MODE`:** Set the proper tracking mode for your location. (Should be `EQ NORTH`)

- **`RATE`:** Set the tracking rate (`SIDEREAL`, `SOLAR`, or `LUNAR`).

:::
::::

```{note}
If you select an object from the database the mount will trackmat the appropriate
rate for the object type but if you slew to an object or enter coordinates manually
the proper rate must be set.
```

#### `SCOPE SETUP`

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu_setup.svg
---
name: nexstar-menu-setup
---
NexStar Menu - Scope Setup
```

:::
:::{grid-item}


:::
::::

#### `UTILITIES`

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu_utilities.svg
---
name: nexstar-menu-utilities
---
NexStar Menu - Utilities
```

:::
:::{grid-item}


:::
::::

#### `USER OBJECTS`

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu_objects.svg
---
name: nexstar-menu-objects
---
NexStar Menu - User Objects
```

:::
:::{grid-item}


:::
::::

### Catalog menus

The hand control contains the following catalogs in its database:

- **Messier:** (#1) Complete list of Messier objects.

- **Caldwell:** (#2) The best NGC and IC objects not in the Messier list.

- **NGC:** (#4) Complete list of objects in the Revised New General Catalog.

- **Planets:** (#5) All 8 planets in our Solar System plus the Moon.

- **Stars:** (#7) A list of the brightest stars from the SAO catalog.

- **Tour:** (#0) A list of interesting objects based on date, time and set filter limits.

- **List:** (#8) All of the objects in the database by type and common name.

::::{grid}
:gutter: 2

:::{grid-item}

```{figure} figures/menu_list.svg
---
name: nexstar-menu-list
---
NexStar Menu - Object Lists
```

:::

:::{grid-item}

- **Named Stars:** Common name listing of the brightest stars in the sky.

- **Named Objects:** Over 50 of the most popular deep sky objects.

- **Double Stars:** Best double, triple and quadruple stars.

- **Variable Stars:** Brightest short period variable stars.

- **Asterisms:** The most recognizable star patterns in the sky.

- **CCD Objects:** Galaxy pairs and clusters well suited for imaging.

- **IC Objects:** Index Catalog deep-sky objects.
  
- **Abell Objects:** Abell Catalog galaxies.

- **Constellation:** IAU recognised constellations.
:::
::::
