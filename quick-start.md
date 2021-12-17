# Quick Start

## Install the package:

{% tabs %}
{% tab title="Node" %}
```
# Install via NPM
npm install weky
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Weky npm can only be used with discord.js v12 and v13. Any other versions will not work.
{% endhint %}

## Run your first function

To run your first function, We will create a Calculator. This will call the `calculator` function from Weky.

Let's take a look at how you might call this function:

```javascript
// messageCreate Event
// Your command that triggers the calculator

const { Calculator } = require("weky");
await Calculator({
    message: message,
    embed: {
        title: 'Calculator | Weky Development',
        color: '#5865F2',
        footer: '©️ Weky Development',
        timestamp: true
    },
    disabledQuery: 'Calculator is disabled!',
    invalidQuery: 'The provided equation is invalid!',
    othersMessage: 'Only <@{{author}}> can use the buttons!'
});
```

{% embed url="https://camo.githubusercontent.com/c4720ae3878282b73a79e2dce845d501a8b7481eac1411ad02d13e2ef8b9c15e/68747470733a2f2f692e696d6775722e636f6d2f444564684848642e706e67" %}
Output
{% endembed %}
