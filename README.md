# Rayk0's VS Code custom css config
Hi, this is my attempt at trying to make VSCode look like Trae / Fleet.

I'm not willing to install the ByteDance's Software on my personal computer since i don't trust in their privacy policies concerning the code i'm writing, but i really like the way they approach the idea of designing an IDE.

That's why i created this repo, which is using some VSCode extensions to make VSCode prettier (in my opinion).

![Screenshot](https://github.com/Rayk0/vs-trae/blob/main/custom-vscode.png?raw=true)

# How to install ?

- VSCode version 1.96 (Tested, maybe it works on older or newer versions)
- Install the [Trae Themes](https://marketplace.visualstudio.com/items?itemName=yanfeixin.trae-themes) extension and select Dark.
- Install the [Custom UI Style](https://marketplace.visualstudio.com/items?itemName=subframe7536.custom-ui-style) extension.
- Install the Geist Mono font from Vercel. (optional)
- Copy my settings.json file to your config (most important part is `custom-ui-style.external.imports` and `workbench.colorCustomizations`)
- Create a folder and copy the `settings.css` and `explorerTitleHandler.js` files.
- Update `custom-ui-style.external.imports` with your own files. ⚠️ Warning ⚠️ Keep the `file://` part
- Run the `Custom UI Style: Reload` command in the command palet (ctrl/cmd + shift + P)

# FAQ
## Troubleshoot
The CSS is specificly made for my personal use. It might not work correctly depending on your tabs positions. It's currently hard to develop some custom VSCode UI and make it work for all.

## Which OS do i need to use ?
I tested on MacOS (M1 Max & Intel) & Windows. But i think any OS will work, you might need to adjust some settings or CSS depending on your OS.

## The CSS is broken, what should i do ?
Again, i only tested on my machine and on MacOS. You might need to adjust some css settings to your likings (`settings.css`).

## Does this repo work with APC and older VSCode versions ?
It might work, but you might need to adjust some things since css classes might vary depending on VSCode's version.

## Do i have any relation with JetBrains (Fleet) or ByteDance (Trae) ?
No, i never worked at any of this companies, and i do not own any rights for their designs. I only tried to make my dev tools look the best way possible by inspiring myself from their tools.

## Will this repo be updated ?
Yes, if i find some issues with the UI and my usage, i will update the CSS accordingly. As mentioned earlier, i'll also try to implement my work for a Windows environment.
