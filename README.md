## Control playback speed and skip sponsored segments, with keyboard or mouse.

### SPEED
- Slider over your own list of speeds (up to ×16). The first value is the left end, the last is the right end.
- Toolbar popup, or an on-screen control at the bottom center of the video.
- Keyboard shortcut to open the on-screen control (Alt+S by default; you can change it, disable it or reset it in the add-on options).
- Use ← → ↑ ↓, Home and End to change speed; Enter closes it.
- Works on regular videos, Shorts and live streams. Can remember your last speed.

### SPONSOR SEGMENTS
- Segments are shown on the video progress bar, with a color you can customize per category.
- For each category (sponsor, self-promotion, interaction reminder, intro, outro, preview, off-topic music, filler) choose: ignore, mark only, show a "Skip" button at the bottom right of the video, or skip automatically.
- Optional "Skipped · Undo" notice after an automatic skip.
- One switch in the popup turns the feature on or off.

### PRIVACY
To find the segments of the video you are watching, the add-on sends to sponsor.ajay.app only the first 4 characters of the SHA-256 hash of the video ID, not the video ID itself. Like any web request, the service also receives your IP address. This data is used only to fetch segments. The add-on collects nothing else, has no analytics and shows no ads. Your settings are stored locally in your browser.

### _CREDITS_
Uses SponsorBlock data licensed under CC BY-NC-SA 4.0 from https://sponsor.ajay.app/.
This add-on is independent and is not affiliated with or endorsed by SponsorBlock or YouTube.
<small>

***Current found bugs:***
- *OperaGX "alt+s" shortcut works kinda weird, it starts both the popup and the browser history if pressed together, if first pressed alt and then "s" it works fine. Recommended to change shortcut to "ctrl+s"*
- *Language button in the options page doesn't show the actual language sometimes. Initial state being "español" but the text shown will be in english if the browser has english as default language. When this happens the language button will work exactly opposite of how it should, saying "english" when displaying spanish text and vice versa.*
- *When a promotional segment is skipped and directly followed by, for example, a self-promotional segment, the user has no way of "undoing" the skipping. Also, if the user clicks on the promotional segment it will always skip it no matter what. The ideal solution would be to, on the first hit, automatically skip, and if the user then clicks on any part of the promotional segment, or goes back and hits said segment for a second time, to let it play while showing the skip button*

*Should probably open some github issues for this if I find the time but meh*

</small>
