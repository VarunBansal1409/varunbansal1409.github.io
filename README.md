# App pages

Privacy policies and support pages for all my apps, served by GitHub Pages at
**https://varunbansal1409.github.io/**. Each app has its own folder:

| App | Home page | Privacy policy | Account deletion |
|---|---|---|---|
| Pixelyt (`com.pixelyt.app`) | https://varunbansal1409.github.io/pixelyt/ | https://varunbansal1409.github.io/pixelyt/privacy.html | No accounts |
| JapDhara (`com.japdhara.japdhara`) | https://varunbansal1409.github.io/japdhara/ | https://varunbansal1409.github.io/japdhara/privacy.html | https://varunbansal1409.github.io/japdhara/delete-account.html |

## Adding another app

1. Create a folder named after the app in lower case, without spaces, such as `workhub/`. The folder name
   becomes part of the app's addresses, so don't rename it once those addresses are in Play Console or in
   the app.
2. Put the app's pages in it: at least `privacy.html`, plus an `index.html` home page and an `icon.png`
   (192 × 192). `pixelyt/` is a working example of all three.
3. Write the privacy policy for what *that* app really does: what it reads, what it stores and where,
   what leaves the device and to whom (servers, analytics, ads, crash reporting, sign-in), permissions,
   retention and deletion, children, and contact details. Don't copy Pixelyt's promises, because Pixelyt
   has no internet access and most apps do.
4. If the app has user accounts, Google Play also asks for an **account deletion** page. Add a
   `delete-account.html` that explains how to request deletion and what is deleted.
5. Add the app to the list in `index.html` and to the table above.
6. Commit and push. Pages republishes in about a minute. Then open the new addresses in a private window.

Keep each address stable once it's registered in Play Console or linked from an app. To change a policy,
edit it in place and update its effective date.
