# item Generator

{% code lineNumbers="true" %}
```yaml
generators:
  item_example:
    settings:
      hologram:
        title: "%gcrazygens_gen_stack%x item example"
        side: UP
      drop_item:
        side: UP # see org.bukkit.block.BlockFace in spigot docs
        itemstack:
          material: COAL
          name: "Coal"
```
{% endcode %}
