---
layout: page
title: Examples
permalink: /examples/
---

The Private Google Calendars plugin provides a widget, shortcode and Gutenberg block. Each one has the same functionality but has to be configured differently. The configurations of the widget and Gutenberg block are almost the same as this can be done with a user interface. The shortcode configuration differs a lot because it has to be specified as attributes of the shortcode.

## Public calendars

Private and public calendars cannot 

Use the `public` and `calendarids` attributes for displaying public calendars in the shortcode.

    [pgc public="true" calendarids="calendar1,calendar2"]

Select the _Public calendars_ options and enter the calendar ID's in the textfield separated by a comma.

## Hide past or future events

### Shortcode

Use the `hidepassed` and `hidefuture` attributes and specify the number of days.

For example to hide all passed events and show events for the next 10 days:

    [pgc hidepassed="0" hidefuture="10"]

### Widget and Gutenberg block

