# Fan card

![Fan light](../images/fan-light.png)
![Fan dark](../images/fan-dark.png)

## Description

A fan card allows you to control a fan entity.

## Configuration variables

All the options are available in the lovelace editor but you can use `yaml` if you want.

| Name                      | Type                                                | Default     | Description                                                                                     |
| :------------------------ | :-------------------------------------------------- | :---------- | :---------------------------------------------------------------------------------------------- |
| `entity`                  | string                                              | Required    | Fan entity                                                                                      |
| `icon`                    | string                                              | Optional    | Custom icon                                                                                     |
| `name`                    | string                                              | Optional    | Custom name                                                                                     |
| `layout`                  | string                                              | Optional    | Layout of the card. Vertical, horizontal and default layout are supported                       |
| `fill_container`          | boolean                                             | `false`     | Fill container or not. Useful when card is in a grid, vertical or horizontal layout             |
| `primary_info`            | `name` `state` `last-changed` `last-updated` `none` | `name`      | Info to show as primary info                                                                    |
| `secondary_info`          | `name` `state` `last-changed` `last-updated` `none` | `state`     | Info to show as secondary info                                                                  |
| `icon_type`               | `icon` `entity-picture` `none`                      | `icon`      | Type of icon to display                                                                         |
| `icon_animation`          | boolean                                             | `false`     | Animate the icon when fan is `on`                                                               |
| `show_percentage_control` | boolean                                             | `false`     | Show a slider to control speed                                                                  |
| `show_oscillate_control`  | boolean                                             | `false`     | Show a button to control oscillation                                                            |
| `show_direction_control`  | boolean                                             | `false`     | Show a button to control direction                                                              |
| `collapsible_controls`    | boolean                                             | `false`     | Collapse controls when off. When used if section, it can produce a layout shift for cards below |
| `tap_action`              | action                                              | `toggle`    | Home assistant action to perform on tap                                                         |
| `hold_action`             | action                                              | `more-info` | Home assistant action to perform on hold                                                        |
| `double_tap_action`       | action                                              | `more-info` | Home assistant action to perform on double_tap                                                  |
