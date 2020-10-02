Template for any page that I want to be consistent in style with my personal website, but that warrants its own repo.

-Add all js script links to default.hbs and all css to custom.css; otherwise you only need to touch index.html and writeup.md

Re: index.html front matter:
  title will be displayed on the page as a header; you don't need to include it in the html or your writeup.

  If you include the sidebar, it'll be the same one as on domonicmilesi.com; otherwise it's just be a footer that says 'made by domonic milesi'

  Include either a writeup link or a value for writeup; if you include both it'll show the writeup. writeup is supposed to be a file path, just so you know; the extension is left off so you don't have to worry about matching .html vs .md when metalsmith converts between the two.

  custom_style needs the directory as well; make sure you include the value as 'css/custom.css'
