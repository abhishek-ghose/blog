To build locally:
* Run `jekyll build` in the source folder.
* Copy contents of `_site` into the compiled folders' `blog` directory. The compiled folder is an entirely different directory, i.e., not a subdir in the source folder. This should map to the `gh-pages` branch in GitHub pages.
* In the compiled folder, copy the `index.html` file from the `blog` directory into the root of the folder.
* Also copy the `_sass` folder from the source folder to a `_sass` folder in the compiled directory. You need this if there have been style related changes, e.g., if you have changed `minima.scss`.
