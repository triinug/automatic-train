<script async src="https://api.beta.glia.com/salemove_integration.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script>
  var settings = {
  "url": "https://api.openweathermap.org/data/2.5/weather?appid=d0c7e498499a2f7a44565f209f05d4c6&q=Tallinn&units=metric",
  "method": "GET",
  "timeout": 0,
};

$.ajax(settings).done(function (response) {
  console.log(response);
});
</script>

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/triinug/automatic-train/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Test

I'm trying to add a link to a page that I have added to the repo.
Here's link: [TestPage](veelyksleht.md)

### Credit Card Options

Below you find the link to all of the credit card offers that we have.
[Credit Card options](CreditCardOptions.md)

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/triinug/automatic-train/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<button
  class="omnibrowse-code-button"
  onclick="document.body.appendChild(document.createElement('sm-visitor-code'))">   Get CoBrowsing code </button>
