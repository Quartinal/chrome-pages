# chrome-pages
Database of all the Chrome protocols, APIs, and pages I can find (exclusively for Chrome OS)! This is a WIP project.

### Protocols

**chrome://** - The most well-known, secure, and documented high-level protocol for Chrome.
  - #### Well-known example pages:
    - #### chrome://extensions (is more of an [SPA](https://developer.mozilla.org/en-US/docs/Glossary/SPA))
    - #### chrome://settings (can be considered both/either an [SPA](https://developer.mozilla.org/en-US/docs/Glossary/SPA) or [MPA](https://asperbrothers.com/blog/spa-vs-mpa/))
      - Example **chrome://settings** pages:
        - #### chrome://settings/syncSetup
        - #### chrome://settings/signOut
        - #### chrome://settings/resetProfileSettings

**chrome-untrusted://** - Used for lower-level and more specialized applications like Crosh and various side panel pages.
  - #### Well-known example pages:
    - #### chrome-untrusted://crosh (used for the [ChromiumOS Shell](https://chromium.googlesource.com/chromiumos/platform2/+/HEAD/crosh/README.md))
    - #### chrome-untrusted://terminal/html/nassh_preferences_editor.html (is more of an [SPA](https://developer.mozilla.org/en-US/docs/Glossary/SPA), used to manage SSH preferences for the ChromeOS terminal application)
    - #### chrome-untrusted://terminal/html/crosh.html (basically an alias page for chrome-untrusted://crosh)
    - #### chrome-untrusted://terminal/html/terminal_ssh.html (used to manage SSH connections for the ChromeOS terminal application, in fact anything after the [hash](https://developer.mozilla.org/en-US/docs/Web/API/URL/hash) gets injected into SSH directly in the form of a command)
    - #### Side panel pages
    - 

### Discord Server Credits
  - Titanium Network (velzie, r58playz, SprinkzMC, writable, CompactCow, etc)
