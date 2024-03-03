<h1>⚫️ CS20 ⚫️ Ordinals on the Credits.com Blockchain </h1>
&nbsp;

<i></i>Version 0.3</i>
&nbsp;

This is a concept that aims to be the beginning for issuing ordinals inscriptions on the Credits Blockchain. Currently, there are several ordinals networks (BRC20, DRC20, LRC20, BSV20) where data is transferred into the blockchain through json and base64 inscriptions. 
&nbsp;

&nbsp;
- <b>Helloworld Ordinals Credits</b> - <a href="https://monitor.credits.com/CreditsNetwork/transaction/125610051.1" target="_blank">Block 125610051.1</a>
&nbsp;

&nbsp;



<h2>Hello ordinals world</h2>
&nbsp;

A distinction is made in this concept between the creation of different ordinals capabilities:
&nbsp;

1. <b>CS20 tokens</b>: JSON inscriptions that allow launching CS20 tokens without using smartcontract or layer2 tokens. These tokens can be minted by multiple wallets.

2. <b>SNS names</b>: Domain names that can be linked to a wallet, web3 and/or NFT for easy sending of tokens and/or viewing of ordinals

3. <b>CSmap</b>: Metaverse on the blockchain of Credits. Following Bitmaps and Dogemaps, where each block in the blockchain represents a piece of land with different parcels (transactions)

4. <b>NFT</b>: Images inscribed as Base64 code. For now, there are format/size limitations for using this option

5. <b>WEB3page</b>: Simple one-page websites on the blockchain of credits

&nbsp;




<h2>Ordinals on the Credits Blockchain</h2>

&nbsp;

Through the following steps, you can easily inscribe, deploy and mint code into the Credits Blockchain

1. <b>Create a wallet -</b> Visit the website <a href="https://wallets.credits.com/" target="_blank">wallet.credits.com</a> and create a wallet
&nbsp;


2. <b>Destination wallet -</b> Once a wallet is created, you will need to enter the address below as the recipient of the transaction: ```CSoooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo```
&nbsp;


3. <b>Amount in CS -</b> Fill in ```0,0001 CS``` as transfer amount
&nbsp;


4. <b>Max fee -</b> Leave this amount at ```0,1 CS```
&nbsp;


5. <b>Show additional fields -</b> Enter the appropriate ```deploy/mint code``` under "user data"
&nbsp;







&nbsp;
&nbsp;




<h2>Mint CS20 tokens</h2>

&nbsp;

The following codes can be used to mint a CS20 token

1. <b>Mint CS20 token CRED -</b> ```{ "p": "cs-20", "op": "mint", "tick": "cred", "amt": "1000" }```*
&nbsp;


2. <b>Mint CS20 token CSX -</b> ```{ "p": "cs-20", "op": "mint", "tick": "csx", "amt": "100000000" }```**
&nbsp;


3. <b>Mint CS20 token IGOR -</b> ```{ "p": "cs-20", "op": "mint", "tick": "igor", "amt": "10000" }```**
&nbsp;


'* <b>CRED</b> &nbsp; Total supply ```21,000,000``` &nbsp; Mint/limit ```1,000```
&nbsp;


** <b>CSX</b> &nbsp; Total supply ```24,947,107,200,000,000``` &nbsp; Mint/limit ```100,000,000```
&nbsp;


*** <b>IGOR</b> &nbsp; Total supply ```1,000,000,000``` &nbsp; Mint/limit ```10,000```
&nbsp;


   
&nbsp;

<h2>Mint SNS domains</h2>

&nbsp;

The following codes can be used to mint a SNS domain

1. <b>Mint SNS domain .CS -</b> ```{ "p": "sns", "op": "reg", "name": "yourname.cs" }```
&nbsp;


2. <b>Mint SNS domain .Credits -</b> ```{ "p": "sns", "op": "reg", "name": "yourname.credits" }```
&nbsp;




   
&nbsp;

<h2>Mint .CSmap</h2>

&nbsp;

The following codes can be used to mint a SNS domain

1. <b>Mint .CSmap -</b> ```{ "p": "csmap", "op": "reg", "name": "0.csmap" }```
&nbsp;


&nbsp;


   
&nbsp;
<h2>Mint NFT/WEB3</h2>
&nbsp;

1. More info in the near future 
   
&nbsp;

<h2>Todo list</h2>
&nbsp;

1. An indexer should be created that filters and clearly lists all ordinals transactions from the Credits Blockchain - <b>Example <a href="https://unisat.io/search" target="_blank">unisat.io/search</a></b>
   
2. A simple one-page-mint-website should be created where users can create a wallet and easily mint/upload ordinals on the Credits Blockchain. Text markdowns for inscribing text is a must for minting text files in the HTML/CSS format! - <b>Example <a href="https://1satordinals/inscribe" target="_blank">1satordinals.com/inscribe</a></b>
   
3. A simple trading platform for trading CS20 tokens, CSmaps and SNS is a must! - <b>Example 1 (DRC20) <a href="https://doggy.market/" target="_blank">doggy.market</a>, Example 2 (DRC20) <a href="https://chikun.market/" target="_blank">chikun.market</a></b>

4. A convenient to use CS20 Google Chrome plugin wallet for sending and receiving BSV20 ordinals - <b>Example 1 (BRC20) <a href="github.com/unisat-wallet/extension/releases/tag/v1.2.7" target="_blank">github.com/unisat-wallet/extension/releases/tag/v1.2.7</a>, Example 2 (BSV20) <a href="github.com/Panda-Wallet/panda-wallet" target="_blank">github.com/Panda-Wallet/panda-wallet</a></b>
   
5. Consideration should be given to forming a relay between the SNS domain names and a CS20 wallet for easy sending of tokens or linking the SNS domain name to an NFT or WEB3page Monitor Credits Blockchain - <b>Example <a href="github.com/ORDNET/BDNS" target="_blank">github.com/ORDNET/BDNS</a></b>

6. To view WEB3pages in a browser, a router must be designed. This router needs to convert inscribed data to HTML for viewing. Also, this router should include a function for easy viewing of an SNS domain (example; ord://yourname.cs) - <b>Example 1 <a href="github.com/shruggr/ordfs-server" target="_blank">github.com/shruggr/ordfs-server</a>, Example 2 <a href="https://www.zin.so/hellozin.sats" target="_blank">www.zin.so/hellozin.sats</a></b>

7. Credits website, decentral products - <a href="https://blockchain.credits.com/" target="_blank">blockchain.credits.com</a>

&nbsp;

<h2>Note</h2>
&nbsp;

1. This is a concept!
   
2. Use the above inscription codes at your own risk
   
3. More information to follow
   
4. Monitor Credits Blockchain - <a href="https://monitor.credits.com/" target="_blank">monitor.credits.com</a>

5. Credits website, central products - <a href="https://credits.com/" target="_blank">credits.com</a>

6. Credits website, decentral products - <a href="https://blockchain.credits.com/" target="_blank">blockchain.credits.com</a>
   
&nbsp;

<h2>Ordinals Websites</h2>
&nbsp;

1. <b>BTC / BRC20</b> - <a href="https://unisat.io/" target="_blank">unisat.io</a>
2. <b>BTC / ARC20</b> - <a href="https://atomicalmarket.com/mint" target="_blank">atomicalmarket.com/mint</a>
3. <b>BSV / BSV20</b> - <a href="https://1satordinals.com/" target="_blank">1satordinals.com</a>
4. <b>LTC / LRC20</b> - <a href="https://litescribe.io/inscribe/" target="_blank">litescribe.io/inscribe</a>
5. <b>ETH / ETH20</b> - <a href="https://ethscriptions.com/" target="_blank">ethscriptions.com</a>
6. <b>TRX / TRC20</b> - <a href="https://trximarkets.com/inscribe" target="_blank">trximarkets.com/inscribe</a>
7. <b>DOGE / DRC20</b> - <a href="https://drc-20.org/inscribe" target="_blank">drc-20.org/inscribe</a>
8. <b>Bellscoins / BEL20</b> - <a href="https://bells.ordinalswallet.com" target="_blank">bells.ordinalswallet.com</a>
9. <b>Celestia - CIAS</b> - <a href="https://www.cias.wtf/" target="_blank">www.cias.wtf</a>
10. <b>AVAS /ASC20</b> -  <a href="https://avascriptions.com/" target="_blank">avascriptions.com</a>
11. <b>WEB3page ordinals templates</b> -  <a href="https://WEB3page.xyz/" target="_blank">WEB3page.xyz</a>
12. <b>Bitmap Metaverse website</b> -  <a href="https://bitmap.community/" target="_blank">Bitmap.community</a>
13. <b>Ordinals Gaming Platform (multichain)</b> -  <a href="https://championstcg.com/" target="_blank">ChampionsTCG.com</a>
14. <b>Ordinals Gaming Wallet (BSV)</b> -  <a href="https://market.handcash.io/" target="_blank">Market.HandCash.io</a>
   
&nbsp;
