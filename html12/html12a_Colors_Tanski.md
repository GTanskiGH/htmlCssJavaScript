**Before you start:** rename this file to `html12a_Colors_lastname.md`, using your own last name. Watch videos 1–3 and use **Part 1** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**

---

# Task 12a — Web Colors (RGB and Hex)

Type your answers on the blank line under each **Answer:**. Don't just copy the study guide. Explain in your own words where a question asks why.

## 1. How screens make color

**a.** A screen turns its red and blue lights all the way up and leaves green off. What color do you see? Why is mixing light called **additive** color?

**Answer:**

With this color combination, the output will be magenta. Mixing light is called **additive** color because the more light each value adds, the brighter the color becomes.

**b.** A classmate says, "Hex has fewer colors than RGB because hex codes use fewer digits." Are they right? Explain using the number of choices for each color.

**Answer:**

Hex codes and RGB values produce the same amount of colors, but hex values use 2 digits (in base-16), while RGB uses 3 digits (in base-10)

## 2. Reading hex codes

**c.** Name the color for each hex code. For the last two, say whether it is a light or dark gray and how you can tell.

| Hex | Color |
|---|---|
| `#FF00FF` | Magenta |
| `#00FFFF` | Cyan |
| `#FFFF00` | Yellow |
| `#CCCCCC` | Light Gray (the use of a letter for the first digit of each pair notes that each of the colors are of a stronger value) |
| `#1A1A1A` | Dark Gray (the use of a number for the first digit of each pair notes that each of the colors are of a weaker value) |

**d.** In `#3C9F12`, which pair is the strongest? What color family will this be?

**Answer:**

The pair that is the strongest is the green pair as its first digit is the highest. The color family of this hex code will be roughly in the green range.


**e.** The CSS color name `lime` and the CSS color name `green` are not the same color. Give the hex code for each.

**Answer:**

`lime` = `#00ff00`          `green` = `#008000`

## 3. Converting between hex and RGB

**f.** Write each color the other way.

| Given | Write it as |
|---|---|
| `rgb(255, 255, 0)` | hex: `#FFFF00`|
| `#0000FF` | rgb: `rgb(0, 0, 255)`|
| `rgb(0, 0, 0)` | hex: `#000000`|
| `#FFFFFF` | rgb: `rgb(255, 255, 255)`|

**g.** Convert the hex pair `C0` to a normal number. Show your work using the rule in section 1.4 (first digit × 16, plus the second digit). Remember C = 12.

**Answer:**

12 * 16 = 192 + 0 = 192

**h.** `#F80` is short hex. Write it out as a full 6-digit hex code.

**Answer:**

`#FF8800`

## 4. Colors in CSS

**i.** Write CSS that does both of these. Use **hex** for one and **rgb** for the other.
- Makes `h1` text red
- Makes the page (`body`) background white

```css

    h1 {
        color: #FF0000;
    }

    body {
        background-color: rgb(255,255,255);
    }

```

**j.** Write a CSS rule for a class called `.overlay` that makes its background **black and half see-through**. Which number controls the see-through part?

```css

    .overlay {
        background-color: rgb(0, 0, 0, 0.5)
    }

```

**Answer:**

The final number controls how transparent a color is.

**k.** Why is yellow text (`#FFFF00`) on a white background (`#FFFFFF`) a bad choice? What would you change?

**Answer:**

Yellow text on a white background is commonly hard to read, so it is best to switch the white out for a darker color or switch the yellow out for a darker color.

## 5. Your own site

**l.** Open the `styles.css` for your DIY website. Pick one color you used (or choose a new one you like). Write it as a hex code, then explain what the red, green, and blue pairs tell you about the color.

**Answer:**

#2a4a5a : This color has a low emphasis on red, a stronger emphasis on green, and a large emphasis on blue, even though all of the colors are dark in nature.

## Closing 12a — Vocabulary

| Term | Your definition |
|---|---|
| RGB | Red, Green, and Blue value system for making colors |
| Hex code | A shortened version of the RGB value system through the us eof a base-16 to make each cone 2 digits instead of 3. |
| Hexadecimal | The base-16 system that uses numbers (used in hex codes to represent color) |
| Additive color | When multiple colors add their values together, the color itself becomes lighter |
| rgba | The standard RGB value system with an added alpha value that controls transparency. |
