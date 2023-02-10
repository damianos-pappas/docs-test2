---
description: Better copy paste in markdown cannot be
---

# Copy paste test

## Adding or editing wiki pages

### In this article <a href="#in-this-article" id="in-this-article"></a>

* [Adding wiki pages](https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages#adding-wiki-pages)
* [Editing wiki pages](https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages#editing-wiki-pages)
* [Adding or editing wiki pages locally](https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages#adding-or-editing-wiki-pages-locally)
* [About wiki filenames](https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages#about-wiki-filenames)

You can add and edit wiki pages directly on GitHub or locally using the command line.

Wikis are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud and GitHub Enterprise Server. For more information, see "[GitHub's products](https://docs.github.com/en/get-started/learning-about-github/githubs-products)."

### Adding wiki pages <a href="#adding-wiki-pages" id="adding-wiki-pages"></a>

1. On GitHub.com, navigate to the main page of the repository.
2. Under your repository name, click  **Wiki**.![Wiki menu link](https://docs.github.com/assets/cb-13213/images/help/wiki/wiki\_menu\_link.png)
3. In the upper-right corner of the page, click **New Page**.![Wiki new page button](https://docs.github.com/assets/cb-6557/images/help/wiki/wiki\_new\_page\_button.png)
4. Optionally, to write in a format other than Markdown, use the Edit mode drop-down menu, and click a different format.![Wiki markup selection](https://docs.github.com/assets/cb-26384/images/help/wiki/wiki\_dropdown\_markup.gif)
5. Use the text editor to add your page's content.![Wiki WYSIWYG](https://docs.github.com/assets/cb-19056/images/help/wiki/wiki\_wysiwyg.png)
6. Type a commit message describing the new file you’re adding.![Wiki commit message](https://docs.github.com/assets/cb-17907/images/help/wiki/wiki\_commit\_message.png)
7. To commit your changes to the wiki, click **Save Page**.

### Editing wiki pages <a href="#editing-wiki-pages" id="editing-wiki-pages"></a>

1. On GitHub.com, navigate to the main page of the repository.
2. Under your repository name, click  **Wiki**.![Wiki menu link](https://docs.github.com/assets/cb-13213/images/help/wiki/wiki\_menu\_link.png)
3. Using the wiki sidebar, navigate to the page you want to change. In the upper-right corner of the page, click **Edit**.![Wiki edit page button](https://docs.github.com/assets/cb-6809/images/help/wiki/wiki\_edit\_page\_button.png)
4. Use the text editor to edit the page's content.![Wiki WYSIWYG](https://docs.github.com/assets/cb-19056/images/help/wiki/wiki\_wysiwyg.png)
5. Type a commit message describing your changes.![Wiki commit message](https://docs.github.com/assets/cb-17907/images/help/wiki/wiki\_commit\_message.png)
6. To commit your changes to the wiki, click **Save Page**.

### Adding or editing wiki pages locally <a href="#adding-or-editing-wiki-pages-locally" id="adding-or-editing-wiki-pages-locally"></a>

Wikis are part of Git repositories, so you can make changes locally and push them to your repository using a Git workflow.

#### Cloning wikis to your computer <a href="#cloning-wikis-to-your-computer" id="cloning-wikis-to-your-computer"></a>

Every wiki provides an easy way to clone its contents down to your computer. Once you've created an initial page on GitHub, you can clone the repository to your computer with the provided URL:

```shell
$ git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.wiki.git
# Clones the wiki locally
```

Once you have cloned the wiki, you can add new files, edit existing ones, and commit your changes. You and your collaborators can create branches when working on wikis, but only changes pushed to the default branch will be made live and available to your readers.

### About wiki filenames <a href="#about-wiki-filenames" id="about-wiki-filenames"></a>

The filename determines the title of your wiki page, and the file extension determines how your wiki content is rendered.

Wikis use [our open-source Markup library](https://github.com/github/markup) to convert the markup, and it determines which converter to use by a file's extension. For example, if you name a file _foo.md_ or _foo.markdown_, wiki will use the Markdown converter, while a file named _foo.textile_ will use the Textile converter.

Don't use the following characters in your wiki page's titles: `\ / : * ? " < > |`. Users on certain operating systems won't be able to work with filenames containing these characters. Be sure to write your content using a markup language that matches the extension, or your content won't render properly.
