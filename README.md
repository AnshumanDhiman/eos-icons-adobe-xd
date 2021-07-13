# eos-icons-adobe-xd

An Adobe XD plugin to use all of EOS-icons from within the application

## Steps to build it locally

# Latest

- Clone the repo in the folder of your choice.
- Run `npm i` and `npm run watch`.
- Install [`Adobe UXP Developer Tool`](https://www.adobe.io/photoshop/uxp/guides/uxp-developer-tool/) .
- Open `Adobe XD` and open a document.
- Open UXP Developer Tool.
- Click `Add Existing Plugin`.
- Add the `manifest.json` from the dist folder.
- Click on 3 dot icon and select `Load`.
- Go back to `Adobe XD` and try it out! :)

### FAQs

1. Some icons get distorted. Is it the plugin fault?

Ans. No, follow [this](https://adobexd.uservoice.com/forums/353007-adobe-xd-feature-requests/suggestions/17480839--scaling-tool-scale-stroke-weight-shadow-effect) and [this](https://community.adobe.com/t5/adobe-xd/design-adobe-xd-resize-svg-without-distortion/m-p/10880105].https://community.adobe.com/t5/adobe-xd/design-adobe-xd-resize-svg-without-distortion/m-p/10880105).
Workaround: Toggle `Responsive Resize` before resizing those icons.

If it doesn't help,
then:

- Delete it.
- Paste again.
- Switch off `Responsive Resize`.
- Resize now.
