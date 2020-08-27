# CSS Snippets for Discord

Little tweaks to discord to make it that little bit better, featuring [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

## Installation

### Browser Client

You will need a user style manager like [Stylus](https://github.com/openstyles/stylus).
To remove it, disactivate the user style.

1. Go to [Discord's Website](https://discord.com)
2. Click on the Stylus icon
3. Click on "Write style for: discord.com/this URL"

    ![image](https://i.imgur.com/RS2RT8d.png)

4. Paste your snippet of choice in Stylus
5. Click on "Save"

### Desktop Client

#### Without Client Mods

To remove it, reload the page.

1. On your keyboard, press [Ctrl] [Shift] [i]
2. Click on the "Console" tab
3. Paste yout snippet of choice inside this:

```js
__SECRET_EMOTION__.injectGlobal(`
    // snippet here
`);
```

4. Paste it all in your console
5. Press enter

#### With Client Mods

If you're using Powercord, paste it in the Themes > QuickCSS tab.

If you're using BetterDiscord, paste it in the CustomCSS tab.

If you're using something else, follow their guide on how to add custom css.
