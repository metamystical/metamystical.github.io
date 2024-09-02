## hash-and-sign
Digitally sign text using a mnemonic seed.
Uses the TweetNaCl-js implementaion of Ed25519 DSA (Digital Signature Algorithm) and SHA-512 for hashing the mnemonic seed.

Github page with usage instructions: [hash-and-sign.html](https://metamystical.github.io/hash-and-sign.html)

## hash-and-crypt
Simple encryption using a mnemonic seed.
Uses the TweetNaCl-js implementaion of Salsa20 and Poly1305 for encryption and SHA-512half for hashing the seed.

Github page with usage instructions: [hash-and-crypt.html](https://metamystical.github.io/hash-and-crypt.html)

## shared-secret.github.io
Create a secret password known only to you and another party, without ever communicating it.
Uses the TweetNaCl-js implementaion of Curve25519 Diffie-Hellman key exchange.
Optionally, short text messages may be encrypted/decrypted with the secret password
using Salsa20 and Poly1305.

Github page with usage instructions: [shared-secret.html](https://metamystical.github.io/shared-secret.html)

### Security notes
  <p>The above HTML page, once served to your computer, has no further communication
  with the server or any other entity. No cookies or local data storage are created when
  the pages run in your browser. Therefore, secret data exist only temporarily within
  the browser while it is open, unless manually copied elsewhere.
  The browser cache should be cleared before closing it. The clipboard should
  also be cleared if a secret was copied to it.</p>
  <p>For enhanced peace of mind, save the HTML page to your computer when it is blank and move it
  to an offline computer before using. Review the dowloaded code, which includes the two libraries <i>nacl.min.js</i>
  and <i>nacl-util.min.js</i>, obtained from github user <i>dchest</i> (Dmitry Chestnykh).
  The originals are available at these links along with non-minified (and possibly more recent) versions:</p>
  <ul>
  <li><a href="https://github.com/dchest/tweetnacl-js/releases/tag/1.0.3">tweetnacl-js 1.0.3</a></li>
  <li><a href="https://github.com/dchest/tweetnacl-util-js/releases/tag/v0.15.0">tweetnacl-util-js v0.15.0</a></li>
  </ul>
  <p>TweetNaCl.js was ported from <a href="http://tweetnacl.cr.yp.to/">TweetNaCl</a> / <a href="http://nacl.cr.yp.to/">NaCl.</a></p>



