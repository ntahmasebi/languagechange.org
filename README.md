## Updating the website

Content is in `content`. This is where we change things within Markdown files (`.md`), the HTML is then rendered using Hugo (more on that later)

Within `content`:

    - `events`:  create a new folder within `events`, put an `index.md` file there with the required metadata, and you've created a new event. It's always a good idea to copy-paste an existing event and work from there
    - `posts`: exactly the same as above, but within `posts`
    - `talk`: exactly the same as above, but within `talk`
    - etc

Also within `content`: the `home` directory has a certain number of files. These are the pages that are on the homepage, and they can be edited directly.



## Hugo

This website only renders/compiles with an outdated version of Hugo, namely [v0.48](https://github.com/gohugoio/hugo/releases/tag/v0.48).

Two ways of updating: easy, and less easy.

    *Easy*: in the root folder (the one where this `README.md` file is), open a terminal and run `hugo server`. This will create a local, live-updating-upon-any-change version of the website at http://localhost:1313/ . Once you're happy with the changes and see that the website works, go to the step below.
    *Less easy*: in the root folder (the one where this `README.md` file is), open a terminal and run `hugo`. This will build the website. Then, go to the next step.
    *Final step*: a static version of the website is generated in `public`. This is the HTML that you need to upload on the webserver. 



