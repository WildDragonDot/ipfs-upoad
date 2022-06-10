# js

Everything about javascript

Essential JS CDN for referencing, currently consist of:

- jquery 3.6.0 dist<br>
- web3 3.0.0 dist<br>
- moment 2.29.2<br>
- ipfs-api 26.1.2 dist<br>

<h3>Examples/</h3>

<a href="https://aloycwl.github.io/js/Examples/IPFS_Upload.html">IPFS_Upload.html</a><br>
The only 100% working Javascript to IPFS example currently.<br>
No node.js, no NPM, no react. Simply import from CDN and run the code.<br>
No login is required, it will return the CID.<br>
IPFS HTPP Client is obselete, IPFS API has not.

<a href="https://aloycwl.github.io/js/Examples/IPFS_Upload_web3storage.html">IPFS_Upload_web3storage.html</a><br>
Using web3.storage API to upload in case Infura start charging

<a href="https://aloycwl.github.io/js/Examples/ERC20_Get_Balance.html">ERC20_Get_Balance.html</a><br>
Fetch token from pure javascript using metamask

<a href="https://aloycwl.github.io/js/Examples/Web3_Alchemy_or_Infura.html">Web3_Alchemy_or_Infura.html</a><br>
In environment such as mobile browser or anything without Metamask or related provider<br>
Can only fetch information, if need to write will require memonic phase signing

<a href="https://aloycwl.github.io/js/Examples/IFPS_Upload_Canvas.html">IFPS_Upload_Canvas.html</a><br>
Merge multiple images to canvas and convert it into base64<br>
Convert base64 into a file object and upload to IPFS<br>
Added promise for async to only allow ipfs action after all images are loaded

<a href="https://aloycwl.github.io/js/Examples/Web3_List_Token_Holders_getPastEvents.html">Web3_List_Token_Holders_getPastEvents.html</a><br>
Using ABI and contract address to get all emitted events with the owner addresses<br>
Put them into an unique only array

<a href="https://aloycwl.github.io/js/Examples/Canvas_Scrolling_Background.html">Canvas_Scrolling_Background.html</a><br>
Panaroma landscape background scrolling<br>
Perpetual scrolling with setInterval reset to prevent unintended stoppage