# Placeholders

{% hint style="warning" %}
Anything with brackets need to be replaced

`%crazygenerators_player_generators-[PLAYER_NAME]%` would be  `%crazygenerators_player_generators-notch%`
{% endhint %}

{% hint style="danger" %}
All placeholders will be in the following format `%crazygenerators_[PLACEHOLDER]%` `[PLACEHOLDER]` is replaced with whatever is under placeholder section
{% endhint %}

{% tabs %}
{% tab title="General Placeholders" %}
<table><thead><tr><th width="153.6666259765625">Placeholder</th><th>Description</th></tr></thead><tbody><tr><td><code>server_generators</code></td><td>Displays the amount of generators server wide</td></tr><tr><td><code>generator_stack</code></td><td>Displays the stack size of the generator your currently looking at</td></tr><tr><td><code>generator_stack-[GENERATOR_ID]</code></td><td>Displays the stack size of a generator using the unique id when placed</td></tr><tr><td><code>generator_stack-[GEN_X,GEN_Y,GEN_Z]</code></td><td>Displays the stack size of the generator based on a location</td></tr></tbody></table>
{% endtab %}

{% tab title="Player Placeholders" %}
<table><thead><tr><th width="153.6666259765625">Placeholder</th><th>Description</th></tr></thead><tbody><tr><td><code>player_generators</code></td><td>Displays the amount of generators for the current player</td></tr><tr><td><code>player_generators-[PLAYER_NAME]</code></td><td>Displays the amount of generators for the player specified (use the placeholder above for the current player)</td></tr><tr><td></td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}
