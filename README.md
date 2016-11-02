PageSpeed Images Experiments
===

This is a manually prepared set of experiments to find the maximum image size (dimensions) which is acceptable by PageSpeed Insights (and it doesn't affect scores for Desktop).

The problem that the PageSpeed doesn't like when webmasters use larger images than the viewport of blocks for these images. For example, if you want to show a user's avatar as 150x150 block on the page, but you use 400x400 image to do that.

Quick result
---

We found out that PageSpeed stops to complain about images at their size equals `<viewport> * 2 - 1`px (so, for viewport 145x145px the maximum image size we can provide without penalties is 289x289px).

These results are the subject to change; always try to make your own tests.

Links
---

* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
* [PageSpeed Insights Documentation](https://developers.google.com/speed/docs/insights/about)
