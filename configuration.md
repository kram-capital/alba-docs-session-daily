# Configuration

Our Daily/Session liquidities indicator has a plethora of settings enabling you to configure not only the look and feel of the indicator, but also the functionality so that you can tailor your experience to your exact needs. The indicator aims to be unopinionated about the way that you trade so that it can be moulded around you and the elements of the strategy that you use. Let's start by opening up the configuration options.
## View the settings
Please take a look at the official Tradingview documentation if you are unsure on how to view the configuration settings for the indicators that are applied to your chart and the return to this page for the Daily/Session liquidities specific configuration options.
[!ref target="blank" text="Official Docs"](https://shorturl.at/isyY6)
# Settings Overview
## Inputs Tab

=== Initialisation
![](/assets/img/alba-docs-daily-inputs-1-timezone.png)

UTC (+/-)
:   Time zone differential relative to UTC

Use exchange time zone <!-- TODO Quan label -->
:   Synchronise time zone with exchange


===

### Sessions

==- Click to expand 

![](/assets/img/alba-docs-daily-inputs-2-sessions-mh.png)

High/Low fill mode <!-- TODO Quan label -->
:   Whether the session outline forms a box or contour

Row 1
:   In order from left to right
    - Toggle on/off
    - Label (leave blank for no label)
    - Session start time
    - Session end time
    - Colour of session markings

Row 2
:   In order from left to right
    - Toggle on/off
    - Label (leave blank for no label)
    - Session start time
    - Session end time
    - Colour of session markings

Row 3
:   In order from left to right
    - Toggle on/off
    - Label (leave blank for no label)
    - Session start time
    - Session end time
    - Colour of session markings

Row 4
:   In order from left to right
    - Toggle on/off
    - Label (leave blank for no label)
    - Session start time
    - Session end time
    - Colour of session markings

Row 5
:   In order from left to right
    - Select what type of line makes up the border <!-- TODO Quan label -->
    - Choose a line width for the border

Row 6
:   In order from left to right
    - Background transparency of the session marking
    - Text size of the session label

Alerts when every session begins <!-- TODO Quan label -->
:   Fires an alert at the start of each session

Alerts when sessions' high/low are breached <!-- TODO Quan label -->
:   Fires an alert when a previous sessions' extremes <br /> are breached

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!
===

### Previous Sessions' High/Low Sweeps

==- Click to expand 

![](/assets/img/alba-docs-daily-inputs-3-prev-hi-low-mh.png)

Row 1
:   In order from left to right
    - Enable ATR filter
    - ATR filter length
    - ATR filter multiplier

Row 2
:   In order from left to right
    - Label for bullish IFC candle
    - Colour of bullish IFC candle
    - Label colour for bullish IFC candle
    - Label size for bullish IFC candle

Row 3
:   In order from left to right
    - Label for bearish IFC candle
    - Colour of bearish IFC candle
    - Label colour for bearish IFC candle
    - Label size for bearish IFC candle

Alert when a candle sweeps out a ...
:   Fire an alert when a previous session is swept

Alert Type
:   Configure how you want the alerts to be fired

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

===
### Key Levels
==- Click to expand 

![](/assets/img/alba-docs-daily-inputs-4-key-levels-mh.png)

Show previous day's High/Low
:   Mark the previous day's high (PDH) and low (PDL) on the chart

Row 1
:   In order from left to right
    - PDH/PDL line width
    - PDH/PDL line type
    - Choose whether the line should be extended
    - PDH/PDL line colour

Row 2
:   In order from left to right
    - Previous daily high label
    - Previous daily low label
    - Label text size

Show previous week's High/Low
:   Mark the previous week's high (PWH) and low (PWL) on the chart

Row 1
:   In order from left to right
    - PWH/PWL line width
    - PWH/PWL line type
    - Choose whether the line should be extended
    - PWH/PWL line colour

Row 2
:   In order from left to right
    - Previous weekly high label
    - Previous weekly low label
    - Label text size

Show previous month's High/Low
:   Mark the previous month's high (PMH) and low (PML) on the chart

Row 1
:   In order from left to right
    - PMH/PML line width
    - PMH/PML line type
    - Choose whether the line should be extended
    - PMH/PML line colour

Row 2
:   In order from left to right
    - Previous monthly high label
    - Previous monthly low label
    - Label text size


Show historical High/Low lines and labels
:   Enable the display of historic levels

Alerts when daily/weekly/monthly range is breached
:   Fire alerts when liquidity levels are breached

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

===

### Previous daily/weekly/monthly candle sweeps
==- Click to expand 

![](/assets/img/alba-docs-daily-inputs-4-key-levels-mh.png)

Row 1
:   In order from left to right
    - Enable ATR filter
    - ATR filter length
    - ATR filter multiplier

Row 2
:   In order from left to right
    - Label for bullish IFC candle
    - Colour of bullish IFC candle
    - Label colour for bullish IFC candle
    - Label size for bullish IFC candle

Row 3
:   In order from left to right
    - Label for bearish IFC candle
    - Colour of bearish IFC candle
    - Label colour for bearish IFC candle
    - Label size for bearish IFC candle

Alert when a candle sweeps out a ...
:   Fire an alert when a previous session is swept

Alert Type
:   Configure how you want the alerts to be fired

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

===

 ## Style Tab

![](/assets/img/alba-docs-daily-styles-1.png)

The three settings within the style tab are to globally toggle the visibility of the drawings created by OptiStruct.

Style settings
:   &nbsp;
    - Display or hide all OptiStruct boxes
    - Display or hide all OptiStruct labels
    - Display or hide all OptiStruct lines

Labels on price scale
:   Show the labels of drawing tools on the price scale

Values in status line
:   Show the values of drawing tools in the status line


## Visibility Tab
This is outside of the scope of our software but below is a link where you will find the official documentation.
[!ref target="blank" text="Official Docs"](https://shorturl.at/rGSUZ)