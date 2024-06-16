# Upgradeable Generator with gui

{% code lineNumbers="true" %}
```yaml
generators:
  upgradeable_gui_example:
    settings:
      hologram:
        side: UP
        title: "%gcrazygens_gen_stack%x upgrade gui"
      gui:
        filler: BLACK_STAINED_GLASS_PANE
        upgrades:
          gui_location: 43
          1:
            rows: 3
            deposit:
            - "10 16"
          2:
            rows: 4
            deposit:
            - "current"
            - "19 25"
          3:
            rows: 5
            deposit:
            - "current"
            - "28 33"
          4:
            rows: 6
            deposit:
            - "current"
            - "36 42"
```
{% endcode %}
