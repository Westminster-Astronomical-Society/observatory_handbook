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

## Catalog menus

The hand control contains the following catalogs in its database:

- **Messier:** (#1) Complete list of Messier objects.

- **Caldwell:** (#2) A collection of the best NGC and IC objects not in the Messier list.

- **NGC:** (#4) Complete list of deep-sky objects in the Revised New General Catalog.

- **Planets:** (#5) All 8 planets in our Solar System plus the Moon.

- **Stars:** (#7) A list of the brightest stars from the SAO catalog.

- **List:** (#8) The most popular objects in the database broken down by type and common name

  - **Named Stars:** Common name listing of the brightest stars in the sky.

  - **Named Objects:** Alphabetical listing of over 50 of the most popular deep sky objects.

  - **Double Stars:** List of the most visually stunning double, triple and quadruple stars.

  - **Variable Stars:** List of the brightest short period variable stars.

  - **Asterisms:** Some of the most recognizable star patterns in the sky.

  - **CCD Objects:** List of many interesting galaxy pairs and clusters well suited imaging.

  - **IC Objects:** Complete list of Index Catalog deep-sky objects.
  
  - **Abell Objects:** List of the Abell Catalog galaxies.

  - **Constellation:** List of all 88 constellations.

## Controller menus

### `MENU`

```{mermaid}
graph LR
    A(MENU) --> B(TRACKING)

    A(MENU) --> C(VIEW TIME-SITE)
    A(MENU) --> D(SCOPE SETUP)
    A(MENU) --> E(UTILITIES)
    A(MENU) --> F(USER OBJECTS)
    A(MENU) --> G(GET RA & DEC)
    A(MENU) --> H(GOTO RA & DEC)
    A(MENU) --> I(IDENTIFY)
    A(MENU) --> J(PRECISE GOTO)
```

#### `TRACKING`

```{mermaid}
graph LR
    B(TRACKING) --> B1(MODE)
        B1 --> B11(EQ NORTH)
        B1 --> B12(EQ SOUTH)
    B(TRACKING) --> B2(RATE)
        B2 --> B21(SIDEREAL)
        B2 --> B22(SOLAR)
        B2 --> B23(LUNAR)
```

#### `SCOPE SETUP`

```{mermaid}
graph LR
    D(SCOPE SETUP) --> D1(SETUP TIME-SITE)
    D(SCOPE SETUP) --> D2(ANTI-BACKLASH)
    D(SCOPE SETUP) --> D3(FILTER LIMITS)
    D(SCOPE SETUP) --> D4(DIRECTION BUTTONS)
    D(SCOPE SETUP) --> D5(GOTO APPROACH)
    D(SCOPE SETUP) --> D6(AUTOGUIDE RATES)
    D(SCOPE SETUP) --> D7(OTA ORIENTATION)
    D(SCOPE SETUP) --> D8(MERIDIAN)
    D(SCOPE SETUP) --> D9(MOUNT SETTINGS)
    D(SCOPE SETUP) --> D10(R.A. LIMITS)
```

#### `UTILITIES`

```{mermaid}
graph LR
    E(UTILITIES) --> E1(CALIBRATE MOUNT)
    E(UTILITIES) --> E2(HOME POSITION)
    E(UTILITIES) --> E3(LIGHTS CONTROL)
    E(UTILITIES) --> E4(FACTORY SETTINGS)
    E(UTILITIES) --> E5(VERSION)
    E(UTILITIES) --> E6(GET AXIS POSITION)
    E(UTILITIES) --> E7(GOTO AXIS POSITION)
    E(UTILITIES) --> E8(HIBERNATE)
    E(UTILITIES) --> E9(SUN MENU)
    E(UTILITIES) --> E10(SCROLLING MENU)
    E(UTILITIES) --> E11(SET MOUNT POSITION)
    E(UTILITIES) --> E12(TURN ON/OFF GPS)
    E(UTILITIES) --> E13(TURN ON/OFF RTC)
    E(UTILITIES) --> E14(PEC)
    E(UTILITIES) --> E15(MOVE TO SWITCH)
```

#### `USER OBJECTS`

```{mermaid}
graph LR
    F(USER OBJECTS) --> F1(GOTO SKY OBJECT)
    F(USER OBJECTS) --> F2(SAVE SKY OBJECT)
    F(USER OBJECTS) --> F3(SAVE DB OBJECT)
    F(USER OBJECTS) --> F4(ENTER RA & DEC)
    F(USER OBJECTS) --> F5(GOTO LAND OBJECT)
    F(USER OBJECTS) --> F6(SAVE LAND OBJECT)
```
