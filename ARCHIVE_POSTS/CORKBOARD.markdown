The 10 Best Static Site Generators
1. Hugo
hugo logo

Hugo is on the easier end of the terminal-based static site generators to set up and use. Their documentation, especially on how to install Hugo and get it running, is quite comprehensive and it doesn’t need you to install a new package store first and then install Hugo from.

It has a large amount of prebuilt themes which makes it easier to pick and choose the look you want for your site, and one of the key features that the Hugo team has is its build-speed.

Making a change to your site by adding or editing content, or changing the theme, requires that you “rebuild” the site: that is, run through the process of combining content with a theme into HTML, for every page. Even a small difference in build-speed performance can make the difference between you waiting seconds and you waiting minutes to see the result of a change that you’ve made, and Hugo works hard on being the fastest at this.

If you’re building a site from existing data, then Hugo’s “Data-Driven Content” feature makes it relatively easy to have the content of the site being provided in CSV or JSON formats. This can be a useful way to take some existing data that you wish to expose to the world in a more convenient fashion that they can browse and navigate through without needing to fire up Excel or Google Sheets.

2. Eleventy, or 11ty11ty logo
11ty is one of the newer SSGs but is rocketing up the popularity list. It bills itself as “a simpler static site generator”. However, it does require a reasonable amount of technical familiarity (and its documentation reflects this) but for those who can grasp it, it does things in an elegant way.

11ty is written in JavaScript and so requires node.js to work; you’ll need to install that first if you haven’t already, and then install 11ty from the command line.

11ty takes a strong view on website performance, to the point where they proudly display a performance leaderboard of websites built with it, and it’s very popular among web professionals and those curating and building the open web more generally.

3. Pelicanget pelican logo
Pelican has a rather stripped-out aesthetic but using Python as its underlying programming language, has the potential to be expanded in almost any direction you might want with a little extra programming.

It has support for importing site data from WordPress, which makes it easier than some other SSGs to move from an existing WordPress site into static site generation without losing your current setup. And like the better class of SSGs it is designed to be able to handle an entire website and not primarily for blogging.

Pelican does have a slightly steep learning curve at first, though, which makes it more suited for someone already at least a little familiar with Python. Similarly, you will need a Python installation on your computer already, and no guidance is given for non-developers who don’t have this… but if you are a developer type who already uses Python then Pelican is a good place to start.

4. Nikola
nikola logo

Nikola takes a very “batteries included” approach to static site generation, providing very detailed templates for blogging and full websites, but also image galleries and search among other things.

It has a fairly extensive list of plugins and themes too. Although Nikola does tend towards the more technical end of the market; you’ll need to be fairly confident with Python development to do more than the basics here, but if you are then Nikola does offer more extensibility than many of the alternatives.

The themes list is not very comprehensive, so if you’re looking for something beautiful rather than informative then it may be better to look elsewhere. However, the rebuild speed is faster than most of the other possibilities.

Like Pelican, Nikola presupposes that you already have Python available and does not explain how to make that possible, so if you do not and are on Windows, then you might want to look at one of the other alternatives.

5. GatsbyGatsby logo
Gatsby calls itself a static PWA generator. PWA is the term of art for Progressive Web Apps, which can work offline, be added to the home screen on mobile, and so on. It’s possible to do this with any website, including those generated with other SSGs, but Gatsby provides this support out of the box.

For those familiar with React, the web component library, Gatsby may be a good choice because it is built around it, so you can reuse the familiar environment that you already know — indeed, React’s own website is built with Gatsby.

Gatsby requires both node.js and the version control system git to be installed. They have a fairly detailed set of documentation pages about how to set up a Gatsby environment, including on Windows, but it is rather an involved process if you aren’t familiar with the command line. Also, the documentation mixes up Windows and Linux and Mac instructions all-together, making it a little difficult to follow.

6. Jekyll
Jekyll logo

Jekyll is one of the oldest static site generators but is still under active development, and its popularity largely sparked the flood of SSG innovation that has produced everything else in this list.

One of its claims to fame is that it is built into the Github code hosting service: it is possible to save your content into a Github repository, a cloud drive for code, in a way that Github will run the Jekyll code for you and convert the content into a website without you having to run any code at all.

In this way, the Github Pages service can be used as the host for your static website free of charge, and the documentation for how to set this up is fairly clear and easy to follow.

However, it will still require some familiarity with the git code control system. Of course, it’s also possible to run Jekyll yourself on your own computer, and they provide a set of Windows installation instructions, although Windows is not officially supported.

7. Statiq Web
statiq logo

The Statiq Web is a rather new addition to the ranks of SSGs and is still under fairly heavy development. So it’s best suited for those willing to engage in that process and join the community by feeding back what works well and what doesn’t.

Its unique selling point is that it is built with .NET, so those with some knowledge of that programming stack will find Statiq Web fitting nicely with their existing experience. It is an example project of the more general Statiq Framework, so a more experienced programmer may be able to embrace the larger framework to build something more comprehensive.

8. Publii
Publii logo

Publii, unlike most of the other static site generators here, is not a command-line tool. Instead, it is a desktop application, available for Windows, Mac, and Linux.

You might think of this as something similar to WordPress, except that instead of being a website it is an application that runs on your computer and then generates a static version of the website, ready to be published as the other tools do.

There are built-in publishing tools to push the static website to a variety of existing hosts, such as Netlify and cloud hosting locations. It has an import system for converting an existing WordPress site to Publii, and a marketplace of paid professional-level themes.

The application itself is free and open-source and has an active community of users helping one another on a discussion forum. Publii is the least technical of the static site generators currently on offer, while still having pretty much all of their benefits.  For someone not looking to get into a coding and command-line based approach it is a great solution.

9. WP2Static
wp2static logo

WP2Static takes a rather different approach than other static site generators: it is not strictly a site manager in itself. Instead, it works hand in hand with WordPress to make a static version of a site that is managed by WordPress itself.

In the language of the description above, WP2Static leaves WordPress in charge of your editing and turning your content into HTML by combining it with your themes and templates. Then step into WP2Static to take that HTML and publish it as plain HTML somewhere on the web.

There are some obvious benefits to this: you can keep using the WordPress interface that you’re familiar with, and you have access to all of WordPress’s wide library of themes and plugins.

However, there are downsides with this too: it’s important to move your WordPress installation to somewhere else, otherwise you will lose a majority of the benefits of static site generation.

Having your site be static provides great security benefits because you aren’t using a dynamic product such as WordPress, but with this solution, you are still using WordPress. So it’s important to hide that WordPress away somewhere where it can’t be reached by anyone except you.

The technically-minded can move it to a hidden server, or run WordPress on their local machines. Someone who doesn’t immediately understand how to do that may find it difficult to follow the concepts involved, and it can be confusing to remember that the site that your (hidden) WordPress generates is not the site that the public sees until the publish button is pressed.

However, if you’re very used to the WordPress user interface, or are heavily tied to particular WP plugins or themes which would be difficult to find or make available on another SSG, WP2Static might be the ideal solution.

10. Next.js
Nextjs logo

Next.js is less a generator for static sites, and more a framework for building static applications using React. It supports static site generation (and revamped this support to much improve it in the 9.3 release in early 2020), and if you’re looking to build an application with React and want best-in-class static site generation backing that up, Next.js is a good place to look.

It assumes a good knowledge of both JavaScript and React, so it’s not for the non-technical, and the documentation leans towards a Linux or Mac environment with lip-service paid to Windows users.

But for what it’s worth at, it’s very good, and there is quite a bit of buzz around it which means that it gets heavy development and moves forward in leaps and bounds.

How to Choose the Right One?
There you have it: the list of what to choose from.

But how do you pick the one that’s best for you?

Well, if you’re not interested in getting into the command line, then look at Publii, certainly. If you’re a WordPress expert who’s looking to go static, then WP2Static builds on those extensive skills you already have. If you care about speed then 11ty or Hugo are your places to look.

If you have experience in a particular programming language or environment, choose a static site generator written with that language to make the best use of your existing skills: for Python, use Pelican or Nikola; for Ruby, Jekyll, for .NET, Statiq, for React look at Next.js and Gatsby, and for JavaScript, 11ty.

If you’re moving from an existing WordPress site, be sure to check that your tool of choice has an importer for your WordPress content (most do), and be aware that experimentation is cheap and easy. You can build a test static site with some example content and generate it just on your own computer without anybody else being able to see it.

Try out the tools you like the sound of — they’re all free, and open-source — and then when you’re ready, start looking at places to host your static content.