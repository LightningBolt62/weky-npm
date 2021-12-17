# Fast Type

## Calling the chaoswords function

```javascript
await FastType({
    message: message,
    embed: {
        title: 'FastType | Weky Development',
        description: 'You have **{{time}}** to type the below sentence.',
        color: '#5865F2',
        footer: '©️ Weky Development',
        timestamp: true
    },
    sentence: 'This is a sentence!',
    winMessage: 'sentence',
    loseMessage: 'Better luck next time!',
    cancelMessage: 'You ended the game!',
    time: 60000,
    buttonText: 'Cancel',
    othersMessage: 'Only <@{{author}}> can use the buttons!'
});
```

<table><thead><tr><th>Param </th><th>Description</th><th>Type</th><th data-type="checkbox">Required</th><th>Default</th></tr></thead><tbody><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/Message"><code>message</code></a></td><td>The message that triggered this function.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object">object</a></td><td>true</td><td><code>null</code></td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=title"><code>embed.title</code></a></td><td>The title of the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Calculator | Weky Development</td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=color"><code>embed.color</code></a></td><td>The color of the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>#5865F2</td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=footer"><code>embed.footer</code></a></td><td>The footer of the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>©️ Weky Development</td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=timestamp"><code>embed.timestamp</code></a></td><td>Should there be a timestamp in the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean">boolean</a></td><td>false</td><td><code>true</code></td></tr><tr><td><code>sentence</code></td><td>The sentence to play the game with</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Random</td></tr><tr><td><code>winMessage</code></td><td>The text to display when the user wins the game.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>GG, you have a wpm of <strong>{{wpm}}</strong> and You made it in <strong>{{time}}</strong>.</td></tr><tr><td><code>loseMessage</code></td><td>The text to display when the user loses the game.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Better luck next time!</td></tr><tr><td><code>cancelMessage</code></td><td>The text to display when the user cancels the game.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>You ended the game!</td></tr><tr><td><code>time</code></td><td>The time (in miliseconds) the game will continue for.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number">number</a></td><td>false</td><td>60000</td></tr><tr><td><code>buttonText</code></td><td>The text to display on the 'Cancel' button.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Cancel</td></tr><tr><td><code>othersMessage</code></td><td>The text to display when another user tries to use the button.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Only &#x3C;@{{author}}> can use the buttons!</td></tr></tbody></table>
