# Great icon sources:
https://materialdesignicons.com/
https://thenounproject.com/
https://github.com/athombv/homey-vectors-public

# Tools:
https://svg-path-visualizer.netlify.app/
https://cloudconvert.com/svg-to-png
(For making store images. Upload twice and use settings: 75x75 and 500x500)

## Extract SVG from Homey
1. Get the icon on screen in https://my.homey.app
2. Right click -> Inspect
3. Copy the large text 'url' from the --data CSS property
4. Enter the blob on https://base64.guru/converter/decode
5. Remove the `data:image/svg+xml;base64,` from the fron of the blob
6. Click convert
7. Save output in a .svg file
8. Change the 'fill' attribute from `#313132` to `black`

# Tips
## Transparency
Homey converts anything not-transparent to black. White backgrounds therefore turn black when shown in Homey.
The keyword 'transparent' _is_ supported by Homey but not all tools support it. Better is to use: `fill="none" fill-opacity="0"` for compatibility.


# Homey-SVG-Icons
SVG versions (approximations) of default Homey icons
| Capability    | Icon |
| ------------- | :--: |
| measure_co    | <img src="measure_co.svg" width="200"> |
| measure_co2   | <img src="measure_co2.svg" width="200"> |
| measure_pm25   | <img src="measure_pm25.svg" width="200"> |
| measure_luminance   | <img src="measure_luminance.svg" width="200"> |
| measure_humidity   | <img src="measure_humidity.svg" width="200"> |
| alarm_water   | <img src="alarm_water.svg" width="200"> |

Modified icons for custom capabilities and devices
| Capability / name    | Icon |
| ------------- | :--: |
| [measure_eco2](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_eco2.json)    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/assets/icons/eco2.svg" width="200"> |
| [measure_tvoc](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_eco2.json)    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/assets/icons/tvoc.svg" width="200"> |
| [measure_dust](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_dust.json)    | <img src="measure_dust.svg" width="200"> |
| [measure_pm1](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_pm1.json)    | <img src="measure_pm1.svg" width="200"> |
| [measure_pm10](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_pm10.json)    | <img src="measure_pm10.svg" width="200"> |
| [measure_pm10](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_pm10.json)    | <img src="measure_pm10.svg" width="200"> |
| [measure_luminance_full](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_luminance_full.json)    | <img src="measure_luminance_full.svg" width="200"> |
| [measure_luminance_visible](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_luminance_visible.json)    | <img src="measure_luminance_visible.svg" width="200"> |
| [measure_luminance_ir](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_luminance_ir.json)    | <img src="measure_luminance_ir.svg" width="200"> |
| Gasses    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/gasses/assets/icon.svg" width="200"> |
| Alarm Generic	| <img src="alarm_generic.svg" width="200"> |

Other custom icons
| Name    | Icon |
| ------------- | :--: |
| Output Boolean    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/gpio_output_bool/assets/icon.svg" width="200"> |
| Output Pulse    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/gpio_output_pulse/assets/icon.svg" width="200"> |
| Output PWM    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/gpio_output_pwm/assets/icon.svg" width="200"> |
| Output RTTTL    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/gpio_output_rtttl/assets/icon.svg" width="200"> |
| Output Tone    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/gpio_output_tone/assets/icon.svg" width="200"> |
| Input Analog    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/input_analog/assets/icon.svg" width="200"> |
| Input Switch    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/input_switch/assets/icon.svg" width="200"> |
| P1 meter    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/p1/assets/icon.svg" width="200"> |
| Pulse counter    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/drivers/pulse_counter/assets/icon.svg" width="200"> |
| [measure_distance_mm](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_distance_mm.json)    | <img src="measure_distance_mm.svg" width="200"> |
| [measure_distance_cm](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_distance_cm.json)    | <img src="measure_distance_cm.svg" width="200"> |
| [measure_distance_inch](https://github.com/Joolee/nl.joolee.homey.espeasy/blob/master/.homeycompose/capabilities/measure_distance_inch.json)    | <img src="measure_distance_inch.svg" width="200"> |
| Distance    | <img src="measure_distance.svg" width="200"> |
| unknown    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/assets/icons/unknown.svg" width="200"> |
| ESP Easy    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/assets/icon.svg" width="200"> |
| ESP Easy color    | <img src="https://github.com/Joolee/nl.joolee.homey.espeasy/raw/master/assets/images/logo.svg" width="200"> |
