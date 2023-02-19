# The properties you need to add to each element are:

### div: a red background, white text, a font size of 32px, center aligned, and bold
### p: a green background, white text, and a font size of 18px
### button: an orange background and a font size of 18px

---

## Solution:

### I connected the CSS file to the html using the link tag below
<link rel="stylesheet" href="style.css">

### The 'rel' stands for relationship: which explains how the CSS file is related to the HTML file, and the value is 'stylesheet', which says the aim of this relationship is strictly for styling the html documents.

The 'href' stands for hyper-reference, which references the link of the CSS file here in, style.css.

### After linking the CSS file with the HTML file, I moved on to create a class "external" on the div element like this
<div class="external">Style me via external method</div>

### While on the stylesheet, I added the class external like this
.external
{
	background-color: red;
	color: white;
	font-size: 32px;
	font-weight: bold;
	text-align: center;
}

### Then on the internal css, I created a class 'internal' in the paragraph. Wrapped it in a

<style>
{
	background-color: green;
	color: white;
	font-size: 18px;
}
</style>


### Then on the button, I used an inline CSS property by adding an inline style like this
<button style="background-color: orange; font-size: 18px">Inline Method</button>
