# Cooldowns

The time it takes to complete non-passive game modes is determined by the variables below.

#### Class

* Druid: 0
* Assassin: 1
* Ranger: 2

#### Sentinel Health Points

$$
_{Sentinel}HP = 22 + \frac{_{Sentinel}Level}{3} - _{Sentinel}Class * 4
$$

#### Cooldown

$$
Cooldown = _{Attack}Time + _{Regeneration}Time
$$

$$
Cooldown = \frac{_{Creature}HP}{_{Sentinel}AP} + \frac{300}{_{Sentinel}HP}
$$

{% hint style="success" %}
**Tip:** Druids can reduce the current cooldowns of Assassins by 25% and Rangers by 50% with their Heal ability
{% endhint %}

