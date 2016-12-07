# Project Name

TODO: Write a project description

## Installation

TODO: Describe the installation process

## Usage

TODO: Write usage instructions

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

#Future updates
  put technology quote on a div and use a better color on the text.
  Move the quote.
  Change my name and professional title by removing I am and my name.


  ```zsh
  ➜  cd <username>.github.io
  ```

6. Open this project in Atom.

  ```zsh
  atom .
  ```

1. Back in Atom, open `index.html`. Take a moment to read through index.html and answer these questions for yourself:
  *
  <details>
    <summary>How many stylesheets does this webpage currently have? Where in the project can they be found and edited?</summary>
    <p>There are two stylesheets, `normalize.css` and `main.css`. `normalize.css` is in the `vendor/css` folder because it's a file developed by somebody else (a vendor) and you won't be editing it. `main.css` is in the `assets/css` folder and is the custom styling that you'll spend time adjusting.</p>
  </details>
  *  
  <details>
    <summary>In the `<head>` element, change the `<title>` of the page. Where can you observe the impact of this change?</summary>
    <p>On the tab in the browser, your site will display a new name. It used to be "First Training."</p>
  </details>
  *
  <details>
    <summary>If you were to write some Javascript to handle events on this page, what file would be the correct place to write that code?</summary>
    <p>You'd want to write your custom JS in the `assets/js/app.js` file. Once this file grows big enough you might want to create new JS files in the `assets/js` folder.</p>
  </details>

1. In the `<body>` of the document, replace the `<h1>` tag text with your name and add an image (or gif) of your liking using the `<img>` tag.

6. Now that you've changed the repo, it's time to commit your changes. Back in your terminal, type

  ```zsh
  ➜  git status
  ```
  This shows you the files that have been modified, created, or deleted. Notice that they are listed as `untracked`.

1. Now you're ready to `add` your changes. Type
  ```
  ➜  git add .
  ```
  Now enter `git status`. Notice that your new file has gone from `untracked` to `Changes to be committed`.

1. Next step is committing. Type the following:

  ```
  ➜  git commit -m "first edits to index.html"
  ```
  Now enter `git status` again. Notice that the new status is `Your branch is ahead of 'origin/master' by 1 commit.`. This indicates that your the version of the repo on your computer (aka the __local__ version) includes your changes but the version hosted by GitHub (aka the __remote__ version) does not.

1. To get your changes on to the remote version of the repo, type

  ```
  ➜  git push origin master
  ```
>***Note:*** *`origin` is the given name of the remote repository hosted on GitHub. `master` is the name of the main branch within the repository. (Typically `master` is the branch you update when you're ready to publish changes to the world.)*

  Now `git status` will tell you that `Your branch is up-to-date with 'origin/master'.` __!!!__

2. Check back in on your site to see the improvements deployed!

1. Repeat steps 11 onward at least three times to improve your site and practice this Git workflow.

# Deliverables

On Friday, we will be having a feedback session on your progress on the personal portfolio project. By then we expect to see:

* An updated README.md file. A readme is like the cover to the book of code you've written for this site. Don't publish a book without a cover! Describe this project in a few sentences - what are you trying to achieve with this page, what technologies are you using, etc. [This is a decent template](https://gist.github.com/zenorocha/4526327) for the way that a readme often looks. Make sure to link to the live site and include some sort of image (logo or screenshot). If you need help writing markdown language (the reason the file ends in `.md`), check out [this guide](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
* A "My work" section of the page that includes (or will include) links to projects or training deliverables that you want to highlight.
* A "Contact me" section of the page that includes (at least) a way to email you, a link to your GitHub profile, and a link to your LinkedIn profile.
* Some custom HTML, CSS, JS, and images. Put your own personal flare on the page and add some customizations. These could be really simple changes that add a bit of your aesthetic or they could be larger features like a navbar, a footer, a photo carousel, bootstrap integration, event listeners, or CSS animations. [Google for personal websites](https://www.google.com/search?q=personal+website&espv=2&biw=1280&bih=612&site=webhp&tbm=isch&tbo=u&source=univ&sa=X&ved=0ahUKEwjx-Krl6bfOAhUUI2MKHaoPDUEQsAQIQA&dpr=2#imgrc=OOkEvdqZczSU-M%3A), find one that you like, and imitate it!

We're really looking forward to seeing what you've built by Friday! Please reach out to your peers or instructors if you need help making progress on this project.
