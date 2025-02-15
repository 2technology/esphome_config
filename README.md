# esphome config

### Put this in your main config file

```yaml
substitutions:
  device_name: test_device_lab
  friendly_name: LAB Test Device 13

packages:
  common_files:
    url: https://github.com/2technology/esphome_config
    ref: main # optional
    files: [common/sensor.yaml,
            common/fonts.yaml,
            common/text_sensor.yaml
    ]
```
