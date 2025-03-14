To build locally:
* Run `jekyll build` in the source folder.
* Copy contents of `_site` into the compiled folders' `blog` directory. The compiled folder is an entirely different directory, i.e., not a subdir in the source folder. This should map to the `gh-pages` branch in GitHub pages.
* In the compiled folder, copy the `index.html` file from the `blog` directory into the root of the folder.
* Also copy the `_sass` folder from the source folder to a `_sass` folder in the compiled directory. You need this if there have been style related changes, e.g., if you have changed `minima.scss`.
* Making gifs: while matplotlib can be directly used for this, and is convenient when it works, there are times when it creates lossy gifs (sometimes the image between two frames would seem low-res, but it'll pick up again at the next frame) which I have not been able to fix. In such cases, its just easier to dump individual images and use imagemagick to combine them into a gif, and then use gifsicle to optimize the size (even the most aggressive optimization - with the "O3" flag - works quite well, in the sense that it doesn't lead to a significant drop in quality).
