**Before you start:** rename this file to `html12b_SEO_lastname.md`, using your own last name. Watch videos 4–6 and use **Part 2** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**
Grant Tanski
---

# Task 12b — Search Engine Optimization (SEO)

Type your answers on the blank line under each **Answer:**, or fix the code inside the code boxes. Explain in your own words where a question asks why.

## 1. How a search engine works

**a.** Put the three steps a search engine uses in order, and describe each one in one sentence of your own.

| Step | Name | What happens |
|---|---|---|
| 1 | Crawl | A program follows links across pages to find other pages. |
| 2 | Index | Said program defines what each page is about, and puts them in a massive list. |
| 3 | Rank | On the arrival of a search, the program finds the matching pages and adds the most useful ones. |

**b.** You just built a new page, but **no other page links to it**. Why might a search engine have trouble finding it? (Hint: think about how crawlers find pages.)

**Answer:**

If no other page links to your website, then the crawlers who travel through websites by other pages links will not find yours.

## 2. Organic vs. paid

**c.** You search for "pizza Medina Ohio." The first two results say **Sponsored**. The next ones do not. Which results are organic and which are paid? Which kind can SEO help with?

**Answer:**

The results that specify that they are sponsored are paid, while the rest are organic. SEO can help sort through the unpaid ones to get the most useful information.

**d.** A business owner asks, "Why would I spend time on SEO when I could just pay for ads?" Give one reason SEO is still worth it.

**Answer:**

SEO cretaes organic traffic, which continues to be free and provides customers constantly without having to pay a dime.

## 3. Fix the head

This is the `<head>` of a bakery's home page. It works, but it is weak for SEO.

```html
<head>
  <meta charset="UTF-8">
  <title>Home</title>
</head>
```

**e.** Rewrite it below. Add a strong `<title>`, a meta description, and the viewport meta tag. Make up a name and town for the bakery.

```html

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bakery in Ryeville, OH | Bread & Breakfast</title>
  <meta name="description" content="Pristine pastries and prestigious rooms for any customer. Book a room online.">

```

**f.** Where does the text in your `<title>` show up? Where does the meta description usually show up?

**Answer:**

the title tag shows up in the browser tab, while the meta description tends to be placed under the title link when searching for a website.

## 4. Fix the page

**g.** Rewrite this code to be better for SEO and accessibility. Fix the alt text, the link text, and the file name.

```html
<img src="IMG_4471.jpg" alt="picture">
<a href="page3.html">Click here</a> to see our menu.
```

Your fixed version:

```html

<img src="room-one-front-view.jpg" alt="Layout and amenities of first room">
<a href="menu.html">Click here</a> to see our menu.

```

**h.** A page has three `<h1>` tags: one for the logo, one for the page title, and one for the footer. What is wrong, and how should the headings be set up?

**Answer:**

A page cannot have more than one h1 tag. One h1 should be provided to the main atention of the page, and the rest should be h2 tags.

## 5. Spot the problem

**i.** Here is a meta description someone wrote:

`content="cheap shoes cheap shoes best cheap shoes buy cheap shoes cheap shoes near me"`

What is this called? What will a search engine do about it? Rewrite it as a good description.

**Answer:**

If a keyword stuffing incident happens like the one above, the search engine will mark it as spam and hurt its chances as being displayed. 

Rewrite = `content="best cheap shoes to buy near me"`

**j.** Name **two** SEO choices that also help people who use screen readers. Explain how each one helps both.

**Answer:**

The alt text can help screen readers to understand what an image represents, while the heading order allows screen readers to determine the rough page outline.


## 6. Your own site

**k.** Write a `<title>` and a meta description for the `index.html` of your DIY website. Then add them to your real `index.html` and push it.

```html

<head>
  <meta charset="UTF-8">
  <title>Grant Tanski's Art Portfolio | Home</title>
  <meta name="description" content="a curated selection of highlights from my Daily Doodles project">
</head>

```


## Closing 12b — Vocabulary

| Term | Your definition |
|---|---|
| SEO | Search Engine Optimization is when html tags help web browsers to provide website rankings. |
| Crawler (spider) | A robot creates by a search engine that follows links between pages to find other pages.|
| Organic results | Search browser website rankings that come from SEO methods instead of paid sponsoring.|
| Meta description | The description that appears below a link when searching for websites.|
| Keyword stuffing | A description in which keywords are repeated and spammed together (detracts from the website ranking).|
| SERP | The Search Engine Results Page is the page that pops up when searching for a website.|
