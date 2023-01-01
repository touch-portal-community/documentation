# Touch Portal - Get Started - Page

A Page is a set of elements (Buttons and Sliders), displayed in a grid, that you will be able to
interact with from your device

Touch Portal lets you create up to 2 Pages with the free version, but that limit gets blown out with
the Pro upgrade, leaving you the ability to create as many as you want

By default, Touch Portal creates the `(main)` Page that can't be deleted. It will be the one loaded
when you open Touch Portal on your device. If you want to go to another Page, you'll have to create
a [Button that will navigate](https://www.touch-portal.com/blog/post/tutorials/navigating-multiple-pages-v3.php) to it

## Config

### Grid

#### Size

Number of Columns
Number of Rows

The number of cells is limited to 8 for the free version and goes up to 110 with the Pro upgrade

#### Maximize Button space

The Buttons or Sliders will take all the available space if this is enabled, they will remain square
cells otherwise

#### Group Buttons

Buttons will have a square cell and be grouped (stacked) both horizontally and vertically

#### Grid margin

Margin applied to the Page perimeter

#### Button spacing

Margin applied between each Button (horizontally and vertically)

### Background

#### Color

Apply a simple color as the background

#### Image

Set an image as the Page background. The size of the image depends on which device you use

The exact size can be found in `Touch Portal > Settings > Info > Last Device BG width/height`

### Auto Navigation

[Navigate to that Page on certain conditions](https://www.touch-portal.com/blog/post/tutorials/automatic-switching-pages-on-touch-portal.php)

#### Types

##### No auto navigation

Do not navigate automatically to that Page

Default value

##### Go to this Page by default

Load this Page when you start Touch Portal on your device

##### When application filename contains

Load this Page when the focused application's executable file contains what you type in the
textfield (ex: to target Chrome, type `chrome.exe`)

##### When application title contains

Load this Page when the focused application's title contains what you type in the textfield (ex: to
target a Youtube tab in Chrome, type ` - Youtube`)

#### Do not allow auto navigation

Disable auto navigation feature when your device is displaying that specific Page

### Upgrades

Page Upgrades are visual enhancements

#### Edges Graphics Upgrade

##### Color Rows or Columns

Lets you set a color for one or multiple Rows or Columns

##### Page Border

Lets you set the border (top, bottom, left AND right) color and thickness of the Page

##### Single Side Border

Lets you set the border (top, bottom, left OR right) color and thickness of the Page

#### RGB Graphics Upgrade

This Upgrade will allow you to apply some animated RGB borders to your Page

##### Pulsating Single Color RGB Page Border

Lets you pick 1 color as the border with a pulsating effect based on the chosen color

You can also adjust its thickness and roundness

##### Pulsating Double Color RGB Page Border

Lets you pick 2 colors as the border with a pulsating effect based on the chosen colors

You can also adjust its thickness and roundness

##### Rainbow RGB Page Border

Will apply a border with a pulsating effect based on the rainbow colors

You can also adjust its thickness, roundness and the speed (the speed being the time for the
animation to complete a cycle)

##### Animated Rainbow RGB Page Border

Will apply a border with a rotating effect based on the rainbow colors

You can also adjust its thickness, roundness and the speed (the speed being the time for the
animation to complete a cycle)

##### Animated Highlight RGB Page Border

Will apply a border with a rotating effect based on the chosen colors

You can also adjust its thickness

## Content

A Page can contain two things:

- Buttons
- Sliders

### Button

A Button can be interacted with by pressing or holding it on your device

#### On Pressed

The set of [Actions](https://www.touch-portal.com/blog/post/tutorials/multi-action-macro-buttons-v3.php) that will be executed when you press the Button on your device

Actions will be executed sequentially, meaning that each Action will be executed in the order they
appear in the Action Flow

#### On Hold

The set of Actions that will be executed while you hold the Button on your device

Only 1 Action can be used, you can also configure a visual change while the Button will be held

#### On Event

Typically used to change the Button visual aspect (title, background color, image, etc..) when a
specific event occurs (ex: Microphone muted in OBS)

#### Configuration

##### Text

Text displayed on the Button

You can customize the font, color, alignment, location, offsets (vertical and horizontal), size and
shadow

##### Image

Image displayed on the Button

You can use any image or choose one from an icon pack. You can also edit it with the [Editor Graphics Upgrade](https://www.touch-portal.com/blog/post/tutorials/what-can-i-do-with-the-icon-editor-graphics-upgrade.php)

Icon full Button size will enable you to tell Touch Portal that you want the image to occupy all the
available space of the Button or not

##### Background

Background color or gradient applied to the Button

You can customize the start and end colors, its orientation and if you want the corners to be
rounded or not

##### Other

###### Size

This lets you customize the cell size for the Button

Number of columns and rows it occupies on the grid

###### Logic Setup

You'll find here the Button's ID and its initial value (`On` or `Off`)

##### Graphic Upgrade

Visual enhancements you can apply to this Button:

- Edges
    - Square Border
    - Rounded Border
    - Max Rounded Border
    - Label Line Background
    - Circle Border
    - Single Sided Border
- Retro LC
    - LC Block
    - LC One Round Corner
    - LC Open Bullet
    - LC Closed Bullet
    - LC Dot
    - LC Line
    - LC Double Line
    - LC Connect Corner
- RGB
    - Pulsating Single Color Border
    - Pulsating Double Color Border
    - Rainbow Border
    - Rainbow Background
    - Gradient Rainbow Border
    - Animated Gradient Rainbow Border
    - Gradient Rainbow Background
    - Animated Gradient Rainbow Background
    - Animated Highlight Border
    - Rainbow Corners

### Slider

A [Slider](https://www.touch-portal.com/blog/post/tutorials/create-your-first-slider.php) is a 1 dimension controller, with a value range from 0 to 100, often used for volume

##### Connectors

The set of Connectors that will react to the changes you make with the value it is connected to

All Connectors will be called in parallel upon value change

##### Settings

###### Bar Settings

You can customize its orientation (Vertical or Horizontal), sides margins, endpoints margins,
container and value area colors, rounded corners, inlay value area and the area used to slide

###### Control Settings

You can customize its visualization:

- None
- Circle (with a color)
- Rectangle (with a color)
- Image

##### Title

Same as Button with one more setting, its location (Hidden, Top or Bottom)

##### Background

Same as Button

##### Image

Same as Button with one more setting, its location (Hidden, Begin or End)

##### Other

###### Size

This lets you customize the cell size for the Slider

Number of columns and rows it occupies on the grid
