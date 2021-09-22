# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false ] `<div><span>hello</div></span>`

b) [false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

It is a software application (ie: text-to-speech) that allows people with visual impairments to use a computer. We need to care about them because screenreaders can expose weaknesses in our code (ie: invalid syntax, wrong semantics).

Sources: 
https://www.nomensa.com/blog/what-screen-reader 
https://www.accessibility-developer-guide.com/knowledge/screen-readers/what-and-why/

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation 
The tag needed will be an <img> but it requires a src (the source of the image) and an alt (label/title of the image) attributes.

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
For the lists you can used either Unordered <ul> or Ordered <ol> tags and the items within the list use the <li> tag. For the links for the websites, the Anchor <a> (with an href attribute) tag is used to insert the link into the the content of the list (aka the art galleries).

c) You want to sell designer hats. You need to receive orders from the user.
<form> and <input>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
A button cannot be a child of another button because it would be placing two buttons ontop of each other. The code will not work.

## Q5 - What is the most generic tag you can use?
<div> and <span>

## Q6 - What do the following achronyms stand for?

a) `a`
Anchor

b) `ol`
Ordered List

c) `ul`
Unordered List

d) `li`
List Items

e) `tr`
Table Row

f) `th`
Table Head

g) `td`
Table Data

## Q7 - Usually, `td` elements are children of what kind of elements?
td are children of tr

## Q8 - What is the difference between td and th?
td is the data put within the table whereas the th is the header of the table where you would put, for example, the content you want in each column.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
img and input.

## Q11 - What is autofilling and why is it important?
Auto filling allows the brwoser to predict the value that is being input. It is important because it leads to better search results for the user.

## Q12 - Which attributes are always present in an img element?
src and alt.

## Q13 - Which attribute is always present for an anchor tag?
href.