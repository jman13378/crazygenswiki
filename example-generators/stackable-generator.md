---
description: >-
  A stackable generator allows the user to stack multiple generators into 1
  block while still providing multiple items.
---

# Stackable Generator

{% code lineNumbers="true" %}
```yaml
generators:
  stackable_example:
    gen_time: 1000
    gen_placer:
      material: COAL
    block:
      material: COAL_BLOCK
    settings:
      hologram:
        title: "%gcrazygens_gen_stack%x stackable"
        side: UP
      stackable:
        max_stack: 26
        min_stack: 2
```
{% endcode %}
