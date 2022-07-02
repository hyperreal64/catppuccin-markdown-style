# catppuccin-markdown-style

This is a custom style for [mixu/markdown-styles](https://github.com/mixu/markdown-styles) using the [Catppuccin](https://github.com/catppuccin/catppuccin) color palette.

I use this for my websites and stuff.

## Example use-case

```bash
sudo npm install -g markdown-styles
git clone https://github.com/hyperreal64/catppuccin-markdown-style.git ~/mywebsite/catppuccin
cd ~/mywebsite/
```

All markdown content would be stored in `~/mywebsite/input`. Then edit `page.html`, which is sort of a template for the page layout. Finally, generate the website with the following command:

```bash
generate-md --layout ./catppuccin --input ./input --output ./output
```

The website is now available in the `./output` directory. Yay!

To see a live instance, visit my website at [https://hyperreal.coffee](https://hyperreal.coffee) and my personal reference base at [https://techne.hyperreal.coffee](https://techne.hyperreal.coffee)
