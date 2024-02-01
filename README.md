# obsidian-sidenote-callout

[中文版](README-zh.md)

Using the built-in callout syntax in Obsidian, it keeps notes clean and is extremely simple to use. Testing page is generaged by [menzi11/BullshitGenerator(github.com)](https://github.com/menzi11/BullshitGenerator)

![Obsidian Nord - light](./images/sidenote-in-obsidian-nord-1.png)

Theme：[Obsidian Nord](https://github.com/insanum/obsidian_nord)

![minimal - dark](./images/sidenote-in-minimal-1.png)

Theme: [minimal](https://github.com/kepano/obsidian-minimal)

## Feature

- Achieve side note effects by rendering callouts with CSS.
- It can be correctly renderred in both Live Preview mode and Reading View.
- Adaptable to multiple themes.

## Usage

Before we use it, download the sidenote-callout.css and add the css to your vault.

If you want the annotation to appear on the left side, you should phrase it like this.

```
> [!NOTE|aside-l] annotation
> annotation on the left side
```

If you want the annotation to appear on the right side, change <kbd>aside-l</kbd> to <aside-r>.

```
> [!NOTE|aside-r] annotation
> annotation on the right side
```

The folding syntax of callouts is also applicable.

```
> [!NOTE|aside-l]+ annotation
> Default-expanded annotations.
```

```
> [!NOTE|aside-r]- annotation
> Default-collapsed annotations.
```

Try different types of callouts.

```
> [!ERROR|aside-l] ERROR Style
> Other style is available too.(important, tip, cite and even your customized callout styles.)
```

## Style Settings

You can customize the style of sidenotes using the Style Settings plugin.

![sidenote-style-setting](./images/setting.png)

For example: 
- Enable Callout Background
- place the sidenote title at the top
- Enable Hide Fold Icon

![Obsidian Nord - light](./images/sidenote-in-obsidian-nord-2.png)

Theme：[Obsidian Nord](https://github.com/insanum/obsidian_nord)

![minimal - dark](./images/sidenote-in-minimal-2.png)

Theme: [minimal](https://github.com/kepano/obsidian-minimal)

## Shortcomings

- The screen can only be fully displayed if it is large enough, and it may not be fully displayed when it is split on a phone or computer.
- Sidenote callout titles should not be too long if the callout-title is not set to top, cause it may cause deformation.
- The support for exporting styles to PDF is in progress.(doing)
- The position of sidenote callout can only be on the side, can not move up and down.(doing)


## Reference

Special thanks

- https://discord.com/channels/686053708261228577/702656734631821413/1155147566615367680
- https://discord.com/channels/686053708261228577/702656734631821413/1073456247849881610