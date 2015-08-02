# Colour

In CSS you can specify colour using:

1. Names, e.g.: `red`, `green`, `blue`.
2. RGB percentage value, e.g.: `rgb(50%, 40%, 25%)`.
3. RGB numeric value, e.g.: `rgb(105, 98, 44)`.
4. HEX values.

## Colour names

CSS supports 147 colour names. List of supported colour names: http://colours.neilorangepeel.com

## RGB percentage value

In CSS most colours can be specified as a mix of 3 colours: red, green and blue. Here is an example of CSS rule:

```css
p {
	color: rgb(80%, 50%, 27%);
}
```

When we see a colour what we really see is a light of a certain colour. The stronger the light - the brigther the colour. In the above example `80%` of the red will give us brighter red, while `27%` of the blue will give darker blue.

## RGB numeric value

You can also use numeric values between 0 to 255:

```css
p {
	color: rgb(204, 128, 69);
}
```

### HEX value

Example:

```css
p {
	color: #cc8045;
}
```

Red: `cc`.
Green: `80`.
Blue: `45`.

`cc`, `80` and `45` are hexidecimal numbers. Hexidecimal numbers:

|-----|-----|
| Hexadecimal number | Decimal number |
|-----|-----|
| `0` | `0` |
| `1` | `1` |
| `2` | `2` |
| `3` | `3` |
| `4` | `4` |
| `5` | `5` |
| `6` | `6` |
| `7` | `7` |
| `8` | `8` |
| `9` | `9` |
| `a` | `10`|
| `b` | `11`|
| `c` | `12`|
| `d` | `13`|
| `e` | `14`|
| `f` | `15`|

To convert `#cc8045` to decimal numbers (we use them in our daily life) do the following:

1. Convert the first `c` to `12`. Then multiply it by `16`: `12 * 16 = 192`.
2. Convert the second `c` to `12`. Then add `12` to `192`: `12 + 192 = 204`.

That's it: `204` is a numeric value for red. Now repeat for green and blue.



