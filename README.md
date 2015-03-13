vomitorium
==========

iOS development build and release scripts, named after the ancient efficient stadium passageways called "vomitorium". "Get your code out quickly".

- make-packages will build a binary, then sign with two provisioning profiles, e.g. AdHoc and AppStore, so you can test the actual build you want to publish. It handles updating the build number using the Apple Generic Versioning tool. Relies on the app.config file.
- tag-release will handle the user visible version number, and the git tags that help you track down which commit a build was built at.
- resign-ipa is a very quick way to resign an ipa with a new provisioning profile.
