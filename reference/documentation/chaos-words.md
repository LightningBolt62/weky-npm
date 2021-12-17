# Chaos Words

## Calling the chaoswords function

```javascript
await ChaosWords({
    message: message,
    embed: {
        title: 'ChaosWords | Weky Development',
        description: 'You have **{{time}}** to find the hidden words in the below sentence.',
        color: '#5865F2',
        field1: 'Sentence:',
        field2: 'Words Found/Remaining Words:',
        field3: 'Words found:',
        field4: 'Words:',
        footer: '©️ Weky Development',
        timestamp: true
    },
    winMessage: 'GG, You won! You made it in **{{time}}**.',
    loseMessage: 'Better luck next time!',
    wrongWordMessage: 'Wrong Guess! You have **{{remaining_tries}}** tries left.',
    correctWordMessage: 'GG, **{{word}}** was correct! You have to find **{{remaining}}** more word(s).',
    time: 60000,
    words: ['hello', 'these', 'are', 'words'],
    charGenerated: 17,
    maxTries: 10,
    buttonText: 'Cancel',
    othersMessage: 'Only <@{{author}}> can use the buttons!'
});

```

<table><thead><tr><th>Param </th><th>Description</th><th>Type</th><th data-type="checkbox">Required</th><th>Default</th></tr></thead><tbody><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/Message"><code>message</code></a></td><td>The message that triggered this function.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object">object</a></td><td>true</td><td><code>null</code></td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=title"><code>embed.title</code></a></td><td>The title of the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>ChaosWords | Weky Development</td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=color"><code>embed.color</code></a></td><td>The color of the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>#5865F2</td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=fields"><code>embed.fied</code></a><code>(1,2,3,4)</code></td><td>Customizable embed fields.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td><p>field1: 'Sentence:'</p><p></p><p>field2: 'Words Found/Remaining Words:'</p><p></p><p>field3: 'Words found:'</p><p></p><p>field4: 'Words:'</p></td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=footer"><code>embed.footer</code></a></td><td>The footer of the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>©️ Weky Development</td></tr><tr><td><a href="https://discord.js.org/#/docs/main/stable/class/MessageEmbed?scrollTo=timestamp"><code>embed.timestamp</code></a></td><td>Should there be a timestamp in the embed.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean">boolean</a></td><td>false</td><td><code>true</code></td></tr><tr><td><code>disabledQuery</code></td><td>The text to display when the calculator is disabled.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Calculator is disabled!</td></tr><tr><td><code>invalidQuery</code></td><td>The text to display when the user provides an invalid equation.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>The provided equation is invalid!</td></tr><tr><td><code>othersMessage</code></td><td>The text to display when a user tries to use someone else's calculator.</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String">string</a></td><td>false</td><td>Only &#x3C;@{{author}}> can use the buttons!</td></tr></tbody></table>
