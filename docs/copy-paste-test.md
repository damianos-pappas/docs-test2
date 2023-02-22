# Copy paste test

## How to Use GitBook for Technical Documentation

This guide will share my experience creating technical documentation using GitBook and act as a de-facto quick-start guide to GitBook.

2 years ago  •  6 min read

[![](https://arctype.com/blog/content/images/size/w50/2021/04/Hanan.JPG)](https://arctype.com/blog/author/hanan/)By [Hanan Younes](https://arctype.com/blog/author/hanan/)

<figure><img src="https://arctype.com/blog/content/images/size/w1050/2021/04/gitbook-1-1.png" alt=""><figcaption></figcaption></figure>

Table of contents

1. [What Is GitBook?](https://arctype.com/blog/gitbook-technical-documentation-guide/#what-is-gitbook)
2. [Why Is GitBook the Best Documentation Solution?](https://arctype.com/blog/gitbook-technical-documentation-guide/#why-is-gitbook-the-best-documentation-solution)
3. [The Three Fundamentals of GitBook](https://arctype.com/blog/gitbook-technical-documentation-guide/#the-three-fundamentals-of-gitbook)
4. [A Step by Step Guide to Creating Your First Documentation on GitBook](https://arctype.com/blog/gitbook-technical-documentation-guide/#a-step-by-step-guide-to-creating-your-first-documentation-on-gitbook)
   1. [Signing Up and Creating Your First Project](https://arctype.com/blog/gitbook-technical-documentation-guide/#signing-up-and-creating-your-first-project)
   2. [Creating and Linking to a GitHub Repository](https://arctype.com/blog/gitbook-technical-documentation-guide/#creating-and-linking-to-a-github-repository)
   3. [Merging Changes to Your GitBook Pages](https://arctype.com/blog/gitbook-technical-documentation-guide/#merging-changes-to-your-gitbook-pages)
   4. [Viewing and Sharing Your Documentation](https://arctype.com/blog/gitbook-technical-documentation-guide/#viewing-and-sharing-your-documentation)

For the past three months, I have had the distinct pleasure of working as an [**Outreachy**](https://outreachy.org/) intern for an open-source project called [**Intermine**](http://www.intermine.org/), where I was tasked with creating new user training documentation. For this project, I entirely rewrote the Intermine user documentation—which included images, code snippets, tables, mathematical formulas, and more—using GitBook. This guide will share my experience creating technical documentation using GitBook and act as a de-facto quick-start guide to GitBook.

### What Is GitBook? <a href="#what-is-gitbook" id="what-is-gitbook"></a>

[**GitBook** ](https://gitbook.com/)is a collaborative documentation tool that allows anyone to document anything—such as products and APIs—and share knowledge through a user-friendly online platform. According to GitBook, “GitBook is a flexible platform for all kinds of content and collaboration.” It provides a single unified workspace for different users to create, manage and share content without using multiple tools. For example:

* Individuals can use GitBook to track their personal projects, add notes or ideas.
* Teams can centralize and share their internal knowledge bases on GitBook, which improves collaboration and makes finding information more convenient.
* Organizations, including [**Arctype**](https://arctype.com/), can create beautiful docs to guide and support their users and contributors.

<figure><img src="https://arctype.com/blog/content/images/2021/04/Arctype-1-1.png" alt="Arctype documentation powered by GitBook"><figcaption><p>Arctype documentation powered by GitBook</p></figcaption></figure>

### Why Is GitBook the Best Documentation Solution? <a href="#why-is-gitbook-the-best-documentation-solution" id="why-is-gitbook-the-best-documentation-solution"></a>

Given that digital documentation solutions have been around since the dawn of the digital age, it is entirely fair to ask, “why does the world need another documentation tool?”—or in other words, “why should anyone use GitBook?” Of course, other good solutions can be utilized to build user and developer documentation, such as [**ReadTheDocs**](https://readthedocs.org/),[ **MKDocs**](https://mkdocs.org/), and[ ](https://docsify.js.org/)[**Docsify**](https://docsify.js.org/). These popular tools share some features with GitBook, including supporting custom domains, PDF export, search, and navigation abilities. However, GitBook outperforms these documentation solutions in many aspects, including but not limited to:

* Superior customization capabilities to reflect any brand’s identity
* Great plugin system­ with almost 700 plugins that extend the default GitBook functionally
* The most convenient GitHub integration you’ll find to easily sync your documentation with GitHub and keep everything up-to-date!‌

Therefore, in a scenario where requirements like advanced branding, customizable UI design, and features extensibility are essential, existing alternatives cannot compete with GitBook.

As a more concrete example, Intermine had some specific requirements for my documentation overhaul project, which included search and customization abilities, as well as markdown support. Similar to the scenario described above, I started comparing several options and ultimately chose Gitbook to create the new user training material because it:

* Comes standard with both a great online [_WYSIWYG_](https://en.wikipedia.org/wiki/WYSIWYG) editor and markdown support
* Allows for team collaboration
* Can be customized to match any organization’s branding
* Offers a base version that is entirely free for personal use, and the paid, premium version can also be licensed to open-source projects free of charge
* Can display your content, publicly or privately, with anyone—including non-GitBook users.
* It can be configured to synchronize your content with GitHub and also create PDF versions of your documentation.
* It supports integration with other tools, such as Slack, Intercom, and Google Analytics.

_Disclaimer: The above list is not comprehensive nor complete._

### The Three Fundamentals of GitBook <a href="#the-three-fundamentals-of-gitbook" id="the-three-fundamentals-of-gitbook"></a>

According to the GitBook documentation, there are some fundamentals that you’ll need to know to start with GitBook. I will demonstrate these basics using the Arctype documentation written in GitBook.

1. **Space:** in GitBook, spaces are projects – public or private - where you can start writing your personal notes, documenting a product, or sharing knowledge-base simultaneously with your team or individually.
2. **Organization:** an organization is a place where one or several projects are stored. If your organization works on many different projects, you can create a space for each one, and you can invite members to join your organization and start collaborating!
3. **GitHub Integration:** you can easily synchronize your work on GitBook with any GitHub repository, which keeps your documentation up-to-date.

### A Step by Step Guide to Creating Your First Documentation on GitBook <a href="#a-step-by-step-guide-to-creating-your-first-documentation-on-gitbook" id="a-step-by-step-guide-to-creating-your-first-documentation-on-gitbook"></a>

Now that we understand the underlying fundamentals of GitBook, we're ready to start creating documentation!

#### Signing Up and Creating Your First Project <a href="#signing-up-and-creating-your-first-project" id="signing-up-and-creating-your-first-project"></a>

First, you need to sign up for GitBook using your email, GitHub, or Gmail account. As you can see in the screenshot below, you will first be prompted to create a new space dedicated to your projects that you can share publicly or with your team. You can also create an organization that might include several projects or spaces.

<figure><img src="https://arctype.com/blog/content/images/2021/04/Gitbook-2-3.png" alt="Initial screen after signing up for GitBook"><figcaption><p>Initial screen after signing up for GitBook</p></figcaption></figure>

I will keep things simple, and you’ll only need to create a new space to follow along. I created a public space, GitBook Tutorial, shown in the following screenshots. The initial page of your new space should look something like this:

<figure><img src="https://arctype.com/blog/content/images/2021/04/new-space-3.png" alt="Starting page for a new space/project Gitbook"><figcaption><p>Starting page for a new space/project Gitbook</p></figcaption></figure>

#### Creating and Linking to a GitHub Repository <a href="#creating-and-linking-to-a-github-repository" id="creating-and-linking-to-a-github-repository"></a>

As previously mentioned, you can integrate your GitBook content with a GitHub repository. So, you will have to [**create a repository**](https://github.com/new) in GitHub – public or private - to link with your new GitBook space or use a pre-existing one. I’ve created a new private repository for the sake of this guide.

<figure><img src="https://arctype.com/blog/content/images/2021/04/Create-a-New-Repository.png" alt="I created a new private repository named GitBook-Tutorial"><figcaption><p>I created a new private repository named GitBook-Tutorial</p></figcaption></figure>

Remember to not edit the new repository on GitHub for now.

<figure><img src="https://arctype.com/blog/content/images/2021/04/Screenshot--1066-.png" alt="screenshot of repository quick-setup on GitHub for GitBook"><figcaption></figcaption></figure>

To set up the GitHub integration, click on the Integrations tab from the left sidebar and then select the GitHub checkbox, which will allow GitBook to access your GitHub account. Now, you must choose the repository that you want to link. Since my
