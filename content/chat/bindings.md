---
title: Chat bindings
---

## How to enable chat bindings

1. In the menu, click on Options > Controls > Key Bindings > Chat Bind and set your chat bind.
{{< expand "Enable chat bindings" >}}
![](https://imgur.com/o6Ti9KO.gif)
{{< /expand >}}
2. Restart the game.
3. Press your set chat bind with letters to activate the bindings. See the [default bindings section]().

## How to change the bindings
1. Go to the folder where the local files are saved.
2. Modify `chat.txt`.

{{< tabs "tabs-os-bindings-location" >}}
{{< tab "Windows" >}}
## Windows
1. Open the "Run" dialog box by pressing `Windows + R`.
2. Type `%localappdata%\BoringManRewrite`
3. Open and modify `chat.txt`. If the file does not exist, create it.
{{< /tab >}}
{{< tab "Linux" >}}
## Linux
// FIXME: linux chat bindings location
{{< /tab >}}
{{< /tabs >}}

## Tips
### Default chat bindings
![](https://imgur.com/z9Jh1eZ.png)

### Emotes
You can include [emotes](/wiki/chat/emotes/) in bindings.  
The list of emotes is:

- `/yeehaw`
- `/barf`
- `/drink`
- `/smoke`
- `/warcry` ([premium](/wiki/dlcs/premium/) only)
- `/letsgo` ([premium](/wiki/dlcs/premium/) only)

Other commands  
Commands can also be written in chat bindings.
- `/kill`
- `/clear`
- `/help`
- `/emojis`
You can also bind console commands such as:

- `/command say "Hello world!"`
- `/command endmatch`
- `/command pause`
- ...

### Emojis
You can set emojis in bindings. See the list of [emojis](/wiki/chat/emojis).

### Bindings for team chat only
Prefix your binding by `^` to make it visible only by your team:

- `^MEDIC!`
- `^Do it! Just do it!`
- `^Saved my life there! Thanks! :heart:`

> {{< icon "exclamation-circle" >}}
> Spamming bindings in chat will result in muting you for a few seconds.