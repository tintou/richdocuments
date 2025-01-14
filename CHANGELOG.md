# Changelog

## 3.7.14

* [#1331](https://github.com/nextcloud/richdocuments/pull/1331) Log the exception so we know what is actually failing @rullzer
* [#1332](https://github.com/nextcloud/richdocuments/pull/1332) Use https by default for the federation service @rullzer
* [#1337](https://github.com/nextcloud/richdocuments/pull/1337) Properly handle cached failed requests in the Federation service @rullzer
* Update dependencies

## 3.7.13

* [#1326](https://github.com/nextcloud/richdocuments/pull/1326) Do not update CSP on calls to files_sharing @rullzer
* [#1327](https://github.com/nextcloud/richdocuments/pull/1327) Handle errors when fetching remote file info more gracefully @juliushaertl
* [#1329](https://github.com/nextcloud/richdocuments/pull/1329) Move federation cache to a distributed one @juliushaertl

## 3.7.12

* [#1178](https://github.com/nextcloud/richdocuments/pull/1178) Show error if trying to open a file on session credential based external storage @juliushaertl
* [#1279](https://github.com/nextcloud/richdocuments/pull/1279) Actually mark wopi entity fields as updated @juliushaertl
* [#1284](https://github.com/nextcloud/richdocuments/pull/1284) Rename document on save as success @eszkadev
* [#1303](https://github.com/nextcloud/richdocuments/pull/1303) Cut of guest names so they fit into the database @nickvergessen
* [#1305](https://github.com/nextcloud/richdocuments/pull/1305) Properly trim trailing slashes from the remote url @juliushaertl
* [#941](https://github.com/nextcloud/richdocuments/pull/941) Be fair about compatiblity of this module @mmaridev
* Update dependencies

## 3.7.11

* [#1256](https://github.com/nextcloud/richdocuments/pull/1256) Adapt built-in CODE url on host address change @mrkara
* [#1269](https://github.com/nextcloud/richdocuments/pull/1269) Increase timeout if proxy is starting @eszkadev
* [#1277](https://github.com/nextcloud/richdocuments/pull/1277) Check proxy status on timeout @eszkadev
* [#1278](https://github.com/nextcloud/richdocuments/pull/1278) Fix possible issues with remote editing
* [#989](https://github.com/nextcloud/richdocuments/pull/989) Show hint about missing capabilities endpoint connection

## 3.7.10

* [#1257](https://github.com/nextcloud/richdocuments/pull/1257) Try to obtain the appdata folder in 1 go @rullzer
* [#1258](https://github.com/nextcloud/richdocuments/pull/1258) Fix compatibility issue with Nextcloud 15 @juliushaertl
* [#1259](https://github.com/nextcloud/richdocuments/pull/1259) Don't use a stream response on an empty file @rullzer
* [#1266](https://github.com/nextcloud/richdocuments/pull/1266) Fix issues with federated editing in global scale setups @juliushaertl
* [#1268](https://github.com/nextcloud/richdocuments/pull/1268) Fix typo when refetching discovery @eszkadev

## 3.7.9

## Fixed

* [#1238](https://github.com/nextcloud/richdocuments/pull/1238) Move to @nextcloud/capabilities and only register default mime types for viewer
* [#1239](https://github.com/nextcloud/richdocuments/pull/1239) Fix compatibility to oracle as a database
* [#1240](https://github.com/nextcloud/richdocuments/pull/1240) Add two more useful placeholders for watermark text @timar
* [#1242](https://github.com/nextcloud/richdocuments/pull/1242) Add French (Switzerland) and Italian (Switzerland) as special case @timar
* [#1243](https://github.com/nextcloud/richdocuments/pull/1243) Add migration to bigint columns
* [#1244](https://github.com/nextcloud/richdocuments/pull/1244) Do not fail if capabilities have not been fetched for the built-in server


## 3.7.8

### Added

* [#1237](https://github.com/nextcloud/richdocuments/pull/1237) Make frame loading timeout configurable through occ

## 3.7.7

### Added

* [#1220](https://github.com/nextcloud/richdocuments/pull/1220) Support opening visio files @timar
* [#1221](https://github.com/nextcloud/richdocuments/pull/1221) Add close method for mobile app integration @juliushaertl

### Fixed

* [#1222](https://github.com/nextcloud/richdocuments/pull/1222) Adjust ui_defaults do be the same across different document types @juliushaertl
* [#1226](https://github.com/nextcloud/richdocuments/pull/1226) Move Collabora endpoint caching to distributed cache @juliushaertl

## 3.7.6

### Added
* [#1211](https://github.com/nextcloud/richdocuments/pull/1211) Passing some UI Defaults to loleaflet frame @merttumer

### Fixed
* [#1198](https://github.com/nextcloud/richdocuments/pull/1198) Use correct call to notify mobile @eszkadev
* [#1210](https://github.com/nextcloud/richdocuments/pull/1210) Fix escaping for edit with message @gary-kim


## 3.7.5

### Added
* [#1137](https://github.com/nextcloud/richdocuments/pull/1137) Add occ richdocuments:activate-config to autoprovision Collabora configurations @ebardie
* [#974](https://github.com/nextcloud/richdocuments/pull/974) Add frontend hooks and expose config/open methods @juliushaertl

### Bugfixes

* [#1055](https://github.com/nextcloud/richdocuments/pull/1055) Fix bug #1054 @SamKer
* [#1095](https://github.com/nextcloud/richdocuments/pull/1095) Make 'Remove user' label localizable @timar
* [#1111](https://github.com/nextcloud/richdocuments/pull/1111) Updated presentation template. @kendy
* [#1133](https://github.com/nextcloud/richdocuments/pull/1133) Use proper base template to be compatible with Nextcloud 20 @juliushaertl
* [#1150](https://github.com/nextcloud/richdocuments/pull/1150) Arm64: Allow auto-enabling Built-in CODE Server on ARM64 @mrkara
* [#1152](https://github.com/nextcloud/richdocuments/pull/1152) Properly check value types when updating watermark settings @juliushaertl
* [#1153](https://github.com/nextcloud/richdocuments/pull/1153) Very minimal document templates for Collabora Online @timar
* [#1154](https://github.com/nextcloud/richdocuments/pull/1154) Use PHP_OS instead of PHP_OS_FAMILY when PHP version < 7.2 @mrkara
* [#1162](https://github.com/nextcloud/richdocuments/pull/1162) Arm64 adaptations @mrkara
* [#1163](https://github.com/nextcloud/richdocuments/pull/1163) Fix platform mismatch error message @mrkara
* [#1164](https://github.com/nextcloud/richdocuments/pull/1164) Do not use isset for checking the class constant @juliushaertl
* [#1169](https://github.com/nextcloud/richdocuments/pull/1169) Template sourced documents support DownloadAsPostMessage @Ashod
* [#1170](https://github.com/nextcloud/richdocuments/pull/1170) No need to get the avatar image since we have one for each user @juliushaertl
* [#1174](https://github.com/nextcloud/richdocuments/pull/1174) Update location of screenshots @timar
* [#1180](https://github.com/nextcloud/richdocuments/pull/1180) Ensures <iframe> contains a non-empty title attribute @pedropintosilva
* [#1192](https://github.com/nextcloud/richdocuments/pull/1192) Lint fix @R0Wi
* [#1194](https://github.com/nextcloud/richdocuments/pull/1194) Use base template for direct editing @juliushaertl
* [#1195](https://github.com/nextcloud/richdocuments/pull/1195) The mobile apps need to handle the hyperlinks themselves. @kendy

## 3.7.4

* Nextcloud 20 compatibility
* [#1055](https://github.com/nextcloud/richdocuments/pull/1055) Fix migrations for missing table columns @SamKer
* [#1077](https://github.com/nextcloud/richdocuments/pull/1077) Hide sharing menu if no share permission is set @juliushaertl
* [#1078](https://github.com/nextcloud/richdocuments/pull/1078) Hide revision history menu on public pages @juliushaertl
* [#1095](https://github.com/nextcloud/richdocuments/pull/1095) Make 'Remove user' label localizable @timar
* [#1111](https://github.com/nextcloud/richdocuments/pull/1111) Updated presentation template. @kendy


## 3.7.3

### Fixed
* [#1023](https://github.com/nextcloud/richdocuments/pull/1023) Fix saving 'disable certificate verification' @CySlider
* [#1059](https://github.com/nextcloud/richdocuments/pull/1059) Fix issue with custom trusted certificates not being applied
* [#1061](https://github.com/nextcloud/richdocuments/pull/1061) Fix not found error when opening share links with edit permission
 

## 3.7.2

### Fixed

* [#1052](https://github.com/nextcloud/richdocuments/pull/1052) Fix regression caused documents to not load

## 3.7.1


### Fixed

* [#1010](https://github.com/nextcloud/richdocuments/pull/1010) Advise installation via 'occ' if it fails from the web interface. @kendy
* [#1015](https://github.com/nextcloud/richdocuments/pull/1015) String update for built-in CODE option @mrkara
* [#1017](https://github.com/nextcloud/richdocuments/pull/1017) Handling of a new error state from proxy.php?status. @kendy
* [#1020](https://github.com/nextcloud/richdocuments/pull/1020) Check for read permission on the file actions @juliushaertl
* [#1022](https://github.com/nextcloud/richdocuments/pull/1022) Update install.md @juliushaertl
* [#1024](https://github.com/nextcloud/richdocuments/pull/1024) Update screenshots @timar
* [#1026](https://github.com/nextcloud/richdocuments/pull/1026) New error state to handle - running on non-glibc based Linux. @kendy
* [#885](https://github.com/nextcloud/richdocuments/pull/885) Move to @nextcloud packages @juliushaertl
* [#1038](https://github.com/nextcloud/richdocuments/pull/1038) Fix issues with Nextcloud 15/16 @juliushaertl


## 3.7.0

### Added
- Add support for built-in CODE server
- Inform user about web server configuration issues
- Document templates: use only one sans-serif font family
- Viewer integration

### Fixed
- Fix CSP violation when collabora server has so-called 'service root'
- Allow connecting to local addresses
- Avoid duplicate save requests
- Avoid additional HTTP request on the files app
- Reduce requests for loaded CSS files
- Fix certificate validation handling
- Be more robust on paths that don't start with a slash
- Bring back IE11 support

## 3.6.0

### Added
- Add demo server selector and show hint about that when Collabora is not setup

### Fixed
- Fix filesystem setup that caused save issues all over the place
- Do not try to recreate a file from a template more than once
- Do not open PDF files by default
- Dependency bumps

## 3.5.1

### Fixed
- Fix issue when shared files were not creating activity/version entries
- Fix bug on public share links
- Dependency bumps

## 3.5.0

### Added

- Implement support for TemplateSource file creation method
- Add occ command to update template files

### Fixed

- Fix inserting images with groupfolders that have ACL configured
- Fix setting cache values when editing federated (@xklonx)
- Dependency bumps

## 3.4.6

### Added
- Force read operation to trigger audit log when issuing a token
- Nextcloud 18 compatibility

## 3.4.5

### Fixed
- Retry putContent operation if locked
- Include locale in the loleaflet lang parameter
- Make sure files created from the same template have a different WOPI file id
- Always use the owner file owner to access for share links
- Make sure Firefox doesn't navigate out of the current directory
- Dependency bumps


## 3.4.4

### Fixed
- Fix issue when creating files from templates
- Make sure files are properly opened after creation


## 3.4.3

### Fixed
- Update translations
- Bump dependencies
- Always open CSV files with collabora (#671)
- Do not use template shipped by core (#670)
- Fix undefined index warning (#652)
- Check key before accessing (#645)
- Move file list access to files app integration (#651)
- Lower log level if the token does not exist (#653)

## 3.4.2

### Fixed
- Remove unneeded logging
- Restore IE11 compatibility
- Fix group selector in settings
- Use Collabora for secure view of images
- Update dependencies

## 3.4.1

### Fixed

- Fix compatibility with PHP 7.0
- Fix bug when federation app was disabled

## 3.4.0

### Added

- Federated document editing
- Watermarking

### Fixed

- General frontend refactoring to fix flaws in files app integration and performance issues
- Check for type when uploading a template
- Use proper public url instead of regular wopi endpoint to fix issues in locked down environments
- Open file directly if only one template is available

## 3.3.15

### Fixed
- Check for file in editor folder only when available
- Add check to only open one document at a time

## 3.3.14

### Fixed
- Pass paste postmessage from collabora to mobile apps
- Fix preview generation on Nextcloud 17 

## 3.3.13

### Fixed
- Improve loading time when opening documents
- Fix admin settings not saving properly

## 3.3.12

### Fixed
- Fix regression from 3.3.11 without URL rewriting

## 3.3.11

### Fixed
- Fix different wopisrc for the same file with loadbalanced collabora instances

## 3.3.10

### Fixed
- Hide full screen button in mobile apps
- Implement message for supporting download as / print in mobile apps

## 3.3.9

### Fixed
- Pass file renaming message to mobile apps
- Only allow view removal for file owners
- Allow clients to trigger Grab_Focus

## 3.3.8

### Fixed
- Fix UI rescaling in webkit
- Fix scrolling behavior on webkit
- Implement support for file renaming
- Allow to use MS Office template formats

## 3.3.7

### Fixed
- Implement new Views_List message
- Allow accessing the Save As web UI on mobile
- Allow UTF8 characters in filenames when creating documents from mobile

## 3.3.6

### Fixed
- Ship new empty presentation template
- Add migration step to replace empty templates after upgrade 

## 3.3.5

### Fixed
- Only allow closing other views with write permissions

## 3.3.4

### Fixed
- Don't generate preview for empty files
- Copy file to temp file for encrypted / object storage
- Remove ghost avatars #462
- Use "Guestname (Guest)" so that names are more distinguishable
- Use actual user id if a logged in user browses a public share link
- Improved logging
- Replace deprecated javascript calls

## 3.3.3

### Fixed
- Avoid scrolling if iframe is visible
- Return proper product name if it is provided
- Fix searching in groups with other user backends

## 3.3.2

### Fixed
- Use valid HTTP status codes
- Fix undefined variable when creating tokens

## 3.3.1

### Fixed
- Bug fix for syntax error on PHP 7.0

## 3.3.0

### Added

- Use product name from collabora capabilities
- Add hide download support for share links
- Use collabora to generate PDF previews
- Better mimetype handling for mobile editing

### Fixed

- Set timeout for editor inactivity
- Set proper extension when creating ooxml files from templates
- Do not open SVG files with collabora by default
- Hide collabora user list on desktop browsers

## 3.2.4

### Fixed

- Only update capabilities on successfull fetch
- Increase timeout when fetching capabilities
- Fix translations on file actions
- Only try to generate previews if convert-to is available
- Trigger favorite action properly
- Set proper nonce on the outer iframe
- Fix guest name input

## 3.2.3

### Fixed
- Check properly if we are in direct editing
- Fix undefined index log warnings
- Fix multipart data when requesting reviews
- Handle UI_Share postmessage from collabora

## 3.2.2

### Added
- Add option to disable certificate validation

### Fixed
- Fix various errors when interacting with the files app
- Show last saved version in the version sidebar
- Make sure the window title is set properly
- Improve admin settings layout
- Allow to uncheck follow current user
- Fix template previews
- Use Nextcloud language instead of locale

## 3.2.1

### Fixed
- Fix issues with mobile editing
- Restore IE11 compatibility
- Hide sidebar when closing the version viewer
- Fix issue when fetching the file model
- Scale Collabora frame to 100% height on mobile
- Updated translations and fix issues with untranslated text

## 3.2.0
- Added: File actions menu in the header
- Added: Handle UI_CreateFile post message
- Added: Handle unreachable collabora instance
- Added: Load capabilities in a background job
- Fixed: Pass proper response to registerFilesMenu
- Fixed: Translation for Insert images
- Fixed: Remove language settings from templates
- Fixed: Better wording for the image file picker
- Fixed: Use first template if none is selected
- Fixed: Proper scroll behaviour on Nextcloud 14/15
- Fixed: Create new text documents from within collabora
- Fixed: Use proper templates on old collabora versions
- Fixed: Convert nextcloud locale to BCP47 languages tag correctly

## 3.1.1
- Fixed: Capabilities fetching when no url is entered
- Fixed: Capabilities timeout of 5 seconds
- Fixed: NC13 compatibility due to missing js capabilities
- Changed: Updated translations

## 3.1.0
- Added: Template picker (if supported by COOL)
- Added: Mobile editing support capability
- Added: Version integration with the Nextcloud sidebar

## 3.0.6
- Added: NC16 compatibility
- Fixed: Translations
- Fixed: NC15 grid view toggle overlay

## 3.0.5
- Fixed: Pass UID for direct tokens (#301)
- Fixed: Do not show nextcloud bar on small screens (#306)
- Fixed: Avatar improvements for editing users (#304)
- Fixed: show password overlay properly (#308)

## 3.0.4
- Fixed: Make php5.6 compatible again (#297)

## 3.03
- Added: Notify clients when page is fully loaded (#291)
- Fixed: Do not show spinner if we nickname chose is visible (#293)
- Fixed:  Disable the vertical swipe to reload gesture (#295)

## 3.0.2
- Fixes: Only show document overlay when document is fully loaded (#283)
- Fixes: Generate assertUrl link with generateurl, so it also works in subfolder installations (#288)
- Fixes: Show displayname on avatar hover (#289)
- Fixes: Do not clear assets on HEAD request (#290)

## 3.0.1
- Fixes: Do not show loading spinner overlay public page if we need a username
- Fixes: Do not duplicate avatars in the top overlay

## 3.0.0
- Bug: use editor to save the user (fixes #184)
- Bug: allow creation of OOXML files if app not in default location (fixes #118)
- Bug: center public edit name

- Fixes: Do not use deprecated OC.webroot
- Fixes: Move to compiled handlebars tempalte to be strict CSP compatible
- Fixes: Do not show building of the interface

- Feature: Allow inserting images directly from Nextcloud
- Feature: Add sharing button to header
- Feature: Use Collabora as a preview provider
- Feature: Show editors in Nextcloud header


## 1.12.38 and 1.12.39
- Bug: fix z-index issue on Nextcloud 13 beta

## 1.12.37
- Feature: Add support for PutRelativeFile for Save As.

## 1.12.36
- Feature: Add avatar to UserExtraInfo (from NC 13)
- Feature: Start listening for standard post messages and ignore deprecated ones
- Feature: Add option to enable the app only for users in a specific group
- Updated translations

## 1.12.35
- Feature: Support for external apps. External apps can now generate a secret token to access richdocuments public API.

## 1.12.34
- Bug: Fix editing publicly shared documents
- Bug: Delete creator/last modifier name from document templates

## 1.12.33
- Feature: Restore 'Enable edit for specific groups' feature, fixes #66
- Feature: Only edit textfiles with Collabora Online, when texteditorapp is disabled
- Feature: Include support for X-LOOL-WOPI-Timestamp
- Bug: Undefined variable 'owneruid'

## 1.12.32
- Bug: Show Display Name of user, not its uid in userlist
- Bug: Do not throw exception when user not found. It might be a public link share.
- Bug: Use the file owner from the share object, if available. Fixes #85.
- Bug: Shorter db index name. Fixes #54.

## 1.12.31
- Bug: Guard encryption support

## 1.12.30
- Feature: Support opening encrypted files
- Bug: Respect OOXML settings again
- Bug: Register the change under user’s name when saving the document

## 1.12.29
- Bug: Fix undefined instanceId

## 1.12.28
- Bug: Allow full screen
- Updated screenshots
- Updated translations

## 1.12.27
- Bug: Fix revision history

## 1.1.26
- Bug: Set the correct language tag expected by JS
- Bug: Replace trailing slash of WOPI URL
- Bug: Try opening readonly documents too
- Bug: Fix revision history
- Feature: Add rtf and txt as supported file formats
- Feature: Add icon to admin page sidebar
- Feature: Add logging and template to unhandled exceptions

## 1.1.25
- Bug: Fix height for revision history viewer
- Feature: Support for multitenancy installations of LibreOffice Online

## 1.1.24
- Bug: Fix undefined PHP notices
- Security: Properly check for password on password protected shares
