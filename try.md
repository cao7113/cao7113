# Try GFM (GitHub Flavored Markdown)

You can use Markdown syntax, along with some additional HTML tags, to format your writing on GitHub.

## Styling text

**bold by`**`**

*italic by `*`*

***all bold and italic by `***`***

**bold with _italic_**

~~Strikethrough by `~~`~~

log<sub>2</sub>10 by `<sub>`

4<sup>2</sup> by `<sup>`

<ins>Underline by `<ins>`</ins>

## Code and quoting

```bash
echo hello
```

color `#ffffff`

> some quote by `>`

— Mona the Octocat

## using tables

| Rank | Languages |
|-----:|-----------|
|     1| JavaScript|
|     2| Python    |
|     3| SQL       |

When a table column contains numbers, it's useful to right-align the column by using the syntax --: below the header row.


---

Add horizontal rule line by 3+ dash `-`

## Collapsed section

<details>
<summary>My top languages</summary>

Some long info here

</details>

<details open>
<summary>Defautl open seciont</summary>

use `<details open> ...</details>` to open collapsed section

</details>


## Comment

You can use HTML comment syntax to add a comment that will be hidden in the output. 

<!-- TO DO: add more details about me later -->

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, add 2 spaces to the end of a line.  
This is a second line.

## Alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.


## Add pictures and images

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

## Links

- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
- https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github