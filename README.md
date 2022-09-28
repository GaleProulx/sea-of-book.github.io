# Welcome to Sea of Book!!!
This is your one-stop-shop for all the software developer writing you never knew you maybe-sort-of want! Read the stories of your peers, help add functionality to the website, or write! The choice is yours in how you want to use this project.

![Website Preview](/images/sea-of-book-preview.png)

Everything on this website is done through [jekyll](https://jekyllrb.com/) which is a "simple, blog-aware, static site generator" or super simple markdown CMS.

# Contributions
Would you like to contribute to this project? Feel free to either submit writing through a "submission" branch or an edit to the website through a "develop" branch. Please don't try to merge with main, pull requests to main will not be accepted.

| Branch | Description |
| :---: | :--- |
| submission | Where you submit a piece of writing. Mention what category you would like the piece to be classified under or mention that you want to create a new category when making a new pull request. |
| develop | Where you would submit an update to the seaofbook website. This can be a styling fix, adding a category, or adding a new feature. |

All you need to know to contribute is either HTML, SCSS (compiled CSS), JavaScript, or Markdown (and the English language).

## Making a Local Testing Environment
Jekyll does have some prerequisites which you can find [here](https://jekyllrb.com/docs/installation/). The process is relatively straight forward for Windows, Linux, and Mac (yes even for newer ARM architecture machines now).

The following commands should get you up and running relatively fast.

```terminal
gem install jekyll bundler
git clone https://github.com/Pinemark-Gale/sea-of-book.github.io.git
cd sea-of-book.github.io
bundle exec jekyll serve --livereload
```

In your terminal/command prompt you should see a URL. Copy and paste said URL into your favorite web browser and you should see a local instance of the website. The ```--livereload```  part of the final command should have the webpage automatically refresh when you save any changes to a project file. (No more manually refreshing your browser web page, yay!)

# Credits
---

Huge help in graphic design by Ian Dupont.

Material Design Palette Generator by kuali.
https://materialpalettes.com/

Chelsea Market (Google) Font by Tart Workshop
https://fonts.google.com/specimen/Chelsea+Market?selection.family=Chelsea+Market

SVG Icons by Captain Icons
https://mariodelvalle.github.io/CaptainIconWeb/

Social Media Icons by Vecteezy
https://www.vecteezy.com/

W3 Schools helped with various CSS questions.

Category organization help from Sharath (WebJeda blog)
https://blog.webjeda.com/jekyll-categories/

Search bar provided by Sharath (WebJeda)
https://blog.webjeda.com/instant-jekyll-search/
