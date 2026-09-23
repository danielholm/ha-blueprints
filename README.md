# ha-blueprints

A collection of Home Assistant blueprints that I have created or adapted from others.
They are shared freely, but are primarily maintained when I run into issues myself.

## Blueprints

Click **Import to Home Assistant** to open a blueprint directly in your Home Assistant installation. Always check the blueprint's requirements and settings before enabling it.

### Automations

#### Room Lighting Control — Slots with Binary Sensors

Turns lights on or activates scenes based on occupancy and selectable modes for morning, day, evening, and night. Supports global conditions and delayed turn-off.

[![Import to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielholm%2Fha-blueprints%2Fmain%2Fautomation%2Farea_occupancy_lights.yaml)

[View blueprint](automation/area_occupancy_lights.yaml)

#### Smart Floor Lighting v2.6

Controls lighting across an entire floor with up to five zones. Turns lights on when motion is detected, supports night scenes and Adaptive Lighting, and turns zones or the entire floor off after inactivity.

[![Import to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielholm%2Fha-blueprints%2Fmain%2Fautomation%2Ffloor-occupancy-light.yaml)

[View blueprint](automation/floor-occupancy-light.yaml)

#### Frigate LLM Notification

Analyses Frigate snapshots and video clips with LLM Vision and sends detailed notifications through the Home Assistant Companion app. Requires, among other things, Frigate, MQTT, and LLM Vision.

[![Import to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielholm%2Fha-blueprints%2Fmain%2Fautomation%2Ffrigate-llm-notification.yaml)

[View blueprint](automation/frigate-llm-notification.yaml)

#### ZHA — IKEA Symfonisk Sound Remote GEN2

Connects an IKEA Symfonisk remote through ZHA to media player controls, volume buttons, and optional actions for single press, double press, and long press.

[![Import to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielholm%2Fha-blueprints%2Fmain%2Fautomation%2Fsymfonisk.yaml)

[View blueprint](automation/symfonisk.yaml)

### Scripts

#### Voice — Calendar Events — Full LLM Script

Retrieves calendar events with the help of an LLM. You can ask about, for example, today's schedule, the upcoming weekend, a specific time, or specific types of events.

[![Import to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielholm%2Fha-blueprints%2Fmain%2Fscript%2F3_voice_calendar_entries_full_llm_sv.yaml)

[View blueprint](script/3_voice_calendar_entries_full_llm_sv.yaml)

#### Voice — Create a Calendar Event — Full LLM Script

Creates calendar events from voice commands with the help of an LLM. Supports titles, dates, start times, default duration, and a limit for how far ahead events can be scheduled.

[![Import to Home Assistant](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanielholm%2Fha-blueprints%2Fmain%2Fscript%2Fvoice_assist_calendar_create.yaml)

[View blueprint](script/voice_assist_calendar_create.yaml)
