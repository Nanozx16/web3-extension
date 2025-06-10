# web3-extension
legacy-web3-extension
An extension that adds MetaMask's legacy window.web3 API to your browser.

Usage
yarn install
yarn build
Load the unpacked extension from dist/unpacked/YOUR_FAVORITE_BROWSER
Test with any build of the MetaMask Extension, version 9.0.1 and later
Dependencies
This extension has a single production dependency: @metamask/legacy-web3

The extension's content script contains the minified source of this dependency as a string literal in order to inject it into web pages as a <script> tag.

The complete, unminified source can be viewed here.

Supported Browsers
Brave
Chrome
Edge
Firefox
