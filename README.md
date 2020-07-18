<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

Contribute
==========

Most common tasks:
* Edit the `.md` files in the `docs` folder.
* Keep the TOC in the [sidebar] up to date.

There is a simple [procedure] to propose simple changes to the [docs] that build the [site].
Simple changes could be things like typo's, grammar or
simplified phrasing hoping that automated translators do a better job.

[procedure]: https://help.github.com/articles/editing-files-in-another-user-s-repository/
[docs]: https://github.com/d-bl/tesselace-to-gf/tree/master/docs
[sidebar]: https://github.com/d-bl/tesselace-to-gf/tree/master/docs/_includes/Sidebar.html
[site]: https://d-bl.github.io/tesselace-to-gf/

Editing content
------------
You might get lost when editing lines like 

    {% include tesselaceSample.html nr="181" ... %}

The numbers in these lines appear as tooltips on the site when hovering over a thumbnail
or previewing the target of a link.
Note that a few image numbers may occur twice.

Preview your changes online
---------------------------

Github recommends installing Jekyll to build and preview your site locally. 
To preview the actual results online, you can:
 
* Fork the project.
* In the about section: change the description to some warning that your repository is a test version.
  This warning will appear in the banner of your version of the pages.
* Select `master branch /docs folder` to configure your own [github pages].
* Work on the master branch of your fork.
* Create a [pull request] between both masters, make it a draft request for early feedback.

[github pages]: https://docs.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source
[pull request]: https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork

Get your master branch in sync again:

* A crude way: remove your fork and start all over again.
  Make sure you don't loose pending changes or whatever in any of your branches.
* For a less crude way you'll need some git desktop client,
  IDE's might have it integrated but that could be overkill for some. 
  This caters for several options. To name one procedure: 
  * [Create a branch](https://www.wikihow.com/Create-a-Branch-on-GitHub)
    from the tip of your current master as a fall-back.
    Otherwise, it can be very hard (though rarely impossible) to recover from a mistake.
  * Checkout the master branch of the `d-bl` repository as local master branch.
  * Push force it to your own public repository.
