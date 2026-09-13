# Root website deployment

The public website is hosted at <https://xiangshang2004.github.io/>.

Website content and the profile README are maintained in
[xiangshang2004/xiangshang2004](https://github.com/xiangshang2004/xiangshang2004).
The `xiangshang2004.github.io` repository contains only the generated website.

Build this source with Jekyll using an empty `baseurl`, then publish the generated
files, including `.nojekyll`, to the publishing repository's `main` branch.
GitHub Pages serves the root of that branch. Do not copy source files, workflow
records, local private files or CV documents into the publishing repository.
