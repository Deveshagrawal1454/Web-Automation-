# Web-Automation-Using-Puppeteer

<p align="center">
<img src="https://user-images.githubusercontent.com/110953/80448571-91919100-88d1-11ea-936a-a8fb1785311e.jpg" alt="Puppeteer WebPerf logo" width="70%"/>
<h1>Automating Web Perf measurement with Puppeteer</h1>
</p>

🕹 <a href="https://pptr.dev">Puppeteer</a> is a Node library which provides a high-level API to control headless Chrome or Chromium over the <a href="https://chromedevtools.github.io/devtools-protocol/">DevTools Protocol</a>. This repository has recipes for automating Web Performance measurement with Puppeteer.

<p>
  These are the basic steps for the projects execution
  <br>
  
1. Create a new project using Javascript/Typescript in NodeJS
2. Integrate puppeteer library
3. Use puppeteer to
a. Launch headful browser and go t o swap.defillama.com
b. Fill the form
- Enter "Arbitrum One" in the "chain" field
- Enter "12" in "You Sell" field
- Enter "WBTC" (Wrapped BTC) in the "select token" field on right hand side to "You Sell" field
- Enter "USDC" (USDC Coin) in the "select token" field in "You Buy" section
- Once you enter this data, a section will appear on right hand side called - "Select a route to perform a swap"
- Select the second option in this section
4. Leave the browser window open. This is the end of the program.

</p>
