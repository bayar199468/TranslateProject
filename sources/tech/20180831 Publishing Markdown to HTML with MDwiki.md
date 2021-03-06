Publishing Markdown to HTML with MDwiki
======

![](https://opensource.com/sites/default/files/styles/image-full-size/public/lead-images/coffee_cafe_brew_laptop_desktop.jpg?itok=G-n1o1-o)

There are plenty of reasons to like Markdown, a simple language with an easy-to-learn syntax that can be used with any text editor. Using tools like [Pandoc][1], you can convert Markdown text to [a variety of popular formats][2], including HTML. You can also automate that conversion process in a web server. An HTML5 and JavaScript application called [MDwiki][3], created by Timo Dörr, can take a stack of Markdown files and turn them into a website when requested from a browser. The MDwiki site includes a how-to guide and other information to help you get started:

![MDwiki site getting started][5]

What an Mdwiki site looks like.

Inside the web server, a basic MDwiki site looks like this:

![MDwiki site inside web server][7]

What the webserver folder for that site looks like.

I renamed the MDwiki HTML file `START.HTML` for this project. There is also one Markdown file that deals with navigation and a JSON file to hold a few configuration settings. Everything else is site content.

While the overall website design is pretty much fixed by MDwiki, the content, styling, and number of pages are not. You can view a selection of different sites generated by MDwiki at [the MDwiki site][8]. It is fair to say that MDwiki sites lack the visual appeal that a web designer could achieve—but they are functional, and users should balance their simple appearance against the speed and ease of creating and editing them.

Markdown comes in various flavors that extend a stable core functionality for different specific purposes. MDwiki uses GitHub flavor [Markdown][9], which adds features such as formatted code blocks and syntax highlighting for popular programming languages, making it well-suited for producing program documentation and tutorials.

MDwiki also supports what it calls "gimmicks," which add extra functionality such as embedding YouTube video content and displaying mathematical formulas. These are worth exploring if you need them for specific projects. I find MDwiki an ideal tool for creating technical documentation and educational resources. I have also discovered some tricks and hacks that might not be immediately apparent.

MDwiki works with any modern web browser when deployed in a web server; however, you do not need a web server if you access MDwiki with Mozilla Firefox. Most MDwiki users will opt to deploy completed projects on a web server to avoid excluding potential users, but development and testing can be done with just a text editor and Firefox. Completed MDwiki projects that are loaded into a Moodle Virtual Learning Environment (VLE) can be read by any modern browser, which could be useful in educational contexts. (This is probably also true for other VLE software, but you should test that.)

MDwiki's default color scheme is not ideal for all projects, but you can replace it with another theme downloaded from [Bootswatch.com][10]. To do this, simply open the MDwiki HTML file in an editor, take out the `extlib/css/bootstrap-3.0.0.min.css` code, and insert the downloaded Bootswatch theme. There is also an MDwiki gimmick that lets users choose a Bootswatch theme to replace the default after MDwiki loads in their browser. I often work with users who have visual impairments, and they tend to prefer high-contrast themes, with white text on a dark background.

![MDwiki screen with Bootswatch Superhero theme][12]

MDwiki screen using the Bootswatch Superhero theme

MDwiki, Markdown files, and static images are fine for many purposes. However, you might sometimes want to include, say, a JavaScript slideshow or a feedback form. Markdown files can include HTML code, but mixing Markdown with HTML can get confusing. One solution is to create the feature you want in a separate HTML file and display it inside a Markdown file with an iframe tag. I took this idea from the [Twine Cookbook][13], a support site for the Twine interactive fiction engine. The Twine Cookbook doesn’t actually use MDwiki, but combining Markdown and iframe tags opens up a wide range of creative possibilities.

Here is an example:

This HTML will display an HTML page created by the Twine interactive fiction engine inside a Markdown file.
```
<iframe height="400" src="sugarcube_dungeonmoving_example.html" width="90%"></iframe>
```

The result in an MDwiki-generated site looks like this:

![](https://opensource.com/sites/default/files/uploads/4_-_mdwiki_site_summary.png)

In short, MDwiki is an excellent small application that achieves its purpose extremely well.

--------------------------------------------------------------------------------

via: https://opensource.com/article/18/8/markdown-html-publishing

作者：[Peter Cheer][a]
选题：[lujun9972](https://github.com/lujun9972)
译者：[译者ID](https://github.com/译者ID)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://opensource.com/users/petercheer
[1]: https://pandoc.org/
[2]: https://opensource.com/downloads/pandoc-cheat-sheet
[3]: http://dynalon.github.io/mdwiki/#!index.md
[4]: https://opensource.com/file/407306
[5]: https://opensource.com/sites/default/files/uploads/1_-_mdwiki_screenshot.png (MDwiki site getting started)
[6]: https://opensource.com/file/407311
[7]: https://opensource.com/sites/default/files/uploads/2_-_mdwiki_inside_web_server.png (MDwiki site inside web server)
[8]: http://dynalon.github.io/mdwiki/#!examples.md
[9]: https://guides.github.com/features/mastering-markdown/
[10]: https://bootswatch.com/
[11]: https://opensource.com/file/407316
[12]: https://opensource.com/sites/default/files/uploads/3_-_mdwiki_bootswatch_superhero.png (MDwiki screen with Bootswatch Superhero theme)
[13]: https://github.com/iftechfoundation/twine-cookbook
