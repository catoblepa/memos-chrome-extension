## Description

Chrome Web Store: <https://chrome.google.com/webstore/detail/memos-bber/cbhjebjfccgchgbmfbobjmebjjckgofe/>

A browser extension that publishes to [Memos](https://usememos.com/). This project is based on a modification of iSpeak-bber. The original author is [DreamyTZK](https://www.antmoe.com/).

## Changelog

2025.09.22 Updated to support Memos v0.25.1 API changes

2024.07.21 Incompatible update — matched to v0.22.3

2024.06.15 Thanks to the kind contributor [PR#44](https://github.com/lmm214/memos-bber/pull/44)

2024.05.20 Updated to match v0.22

2023.09.19 Incompatible update — adjusted to Memos v0.15 "Access tokens" mode.

<img width="483" alt="123" src="https://github.com/lmm214/memos-bber/assets/1472390/4ce2edc2-ce64-44d5-b4ef-d2e79b9d6a1a">

2023.07.16 Added support for Memos v0.14.0 `api/v1`, while remaining compatible with previous APIs.

2023.04.29 A series of improvements to the right-click menu — thanks to @EZForever for PR [#17](https://github.com/lmm214/memos-bber/pull/17)

2023.04.09 Matched v0.12.0 — attachment links changed from filename to publicId.

2023.03.25 Right-click send-text changed to "append mode" (does not refresh already-open pages); added multi-language support (en, zh-cn).

2023.03.19 Image uploads renamed with precise seconds; focus the input box when opening the extension (works with sending text from the right-click menu to the extension, set a shortcut to open the extension, press Ctrl+Enter to save).

2023.03.10 Fixed fetching the latest memo after publishing.

2023.03.09 Added right-click option to send selected text to the Memos input box.

![iShot_2023-03-05](https://user-images.githubusercontent.com/1472390/222957393-fc2e933e-b18f-4e69-a8c0-4609f84a0a90.png)

2023.03.05 Added option to mark a tag as "visible to only me" or "visible to everyone"; image upload filenames now include a timestamp.

2023.02.26 Changed the style of the Memos visibility button. Support for Ctrl/Meta + Enter to save. Clicking the title opens the main site.

2023.02.25 Fixed random memo feature breaking under v0.11.0 (api amount broke, switched to using stats to get total count).

![iShot_2023-02-06_19 16 28](https://user-images.githubusercontent.com/1472390/216958098-1f4fab2a-e77c-41bd-8ba3-5786f42744d7.png)

2023.02.07 After publishing, show the latest memo; added an archive button for each memo.

2023.02.06 Added search button; added image lightbox.

![iShot_2023-02-04_20 42 40](https://user-images.githubusercontent.com/1472390/216768533-4a93124a-666e-4617-a60b-29c826dc1584.png)

2023.02.05 Random memos support specifying a tag (easter egg: if you open the tag list and there is exactly one tag in the input box, clicking the random button will use that tag).

2023.02.04 Added a "random memos" button to wake memories at any time.

2022.11.15 Added insert file/image button; attempted to fix needing to click the small lock icon on first install.

2022.11.13 Added insert todo button.

2022.11.08 Support drag-and-drop attachments (uploaded one by one).

2022.10.24 Added visibility send settings.
