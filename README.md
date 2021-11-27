# Ad Blocker for Spotify Web
This is an experimental, simple chrome extension to remove audio ads on Spotify web player.
It's available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/spotify-ads-remover/mghhlojofjipigjobacbjdngmjafdeim?hl=iw&authuser=0) too.

## How ads are removed
Ads are removed by intercepting and then tampering with Spotify's state machine requests/updates on the fly. 

The states are modified so that states that represent ads are skipped over (pointing to the state afterwards). This is done in `ads_removal.js`.

### This is copy
- ["Original source"](https://github.com/xileftenurb/spotify-web-ads-remover/tree/patch-1)
- I copied and changed the origin so that The issues tab can be used
- All the credits goes to the respective authors

### Disclaimer

Spotify is a trademark of Spotify Technology S.A., registered in the U.S. and other countries. This extension is an independent project developed by us. and has no relationship to Spotify or Spotify Technology S.A.
