# Client

* `AddCallback(string text, function)`

{% tabs %}
{% tab title="Draw" %}
 **hook to draw:** esp, world esp etc.
{% endtab %}

{% tab title="Createmove" %}
**hook to function:** watermark, resolver, popups etc.
{% endtab %}

{% tab title="Fire" %}
**Ragebot shots event:** logs, resolver, shot chams etc.
{% endtab %}
{% endtabs %}

* `LoadScriptFile(string text)`

**`Runs the lua you want.`**

* `UnloadScriptFile(string text)`

**`Disable the lua you want.`**

* `EventLog(string text, int theme)`

**`Creates an Event Log.`**

## **Event Log Themes**

* **0 =** confirmed
* **1 =** unconfirmed
* **2 =** information
* **3 =** buy log

**using:**`EventLog(name, [0, 1, 2, 3])`

