# TobyCall
TobyCall is a Simple P2P Voice Calling Webapp using [PeerJS](https://github.com/peers/peerjs) as its RTC library.  
The demo page can be found at [gg.gg/tobycall](gg.gg/tobycall)

### Browser Support
- **Chrome**: ✓
- **Safari**: ✗ (Any WebRTC application will not work in Safari)
- **Edge**: Untested
- **IE**: Untested
- **Opera**: Untested

## Usage
The first time your browser opens the site (if you are on the demo page), a prompt to access your microphone will appear.  
Note that this prompt will only be shown on *https-enabled* sites on the Chrome browser.
### Receiver:
 1. Wait for the status to show `Awaiting Connection`.
 1. Copy the PeerJS ID under the status message.
 1. Send your ID to the Caller *(through external means)*
 1. When the caller is connected, an alert will pop up. Click `ok` and you should be connected.
 
### Caller:
 1. Wait for the status to show `Awaiting Connection.`
 1. Click the `Connect to Peer` button.
 1. Input the receiver's ID into the prompt.
 1. You should be connected once the receiver dismisses the alert.
