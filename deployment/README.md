# Root website deployment

The public website is hosted at <https://xiangshang2004.github.io/>.

Website content and the profile README are maintained together in
[xiangshang2004/xiangshang2004](https://github.com/xiangshang2004/xiangshang2004).
The separate `xiangshang2004.github.io` repository contains only the Pages
deployment workflow and its README.

After updating the content repository, run **Publish personal website** in the
[publishing repository's Actions tab](https://github.com/xiangshang2004/xiangshang2004.github.io/actions/workflows/pages.yml).
It reads the latest `main`, builds the bilingual site, and publishes it at the
root address. No content edits or additional access token are needed there.

The workflow template is maintained in [root-pages.yml](root-pages.yml).
Its publishing-repository location is `.github/workflows/pages.yml`.
