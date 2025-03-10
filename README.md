==========
Solana SphereView
-----------------

Description:
-------------
Solana SphereView is a web-based visualization tool that uses D3.js and Solana's Web3.js to display
a network of token holders and their SOL transfer activity on the Solana blockchain. It fetches token data,
displays the top 100 token holders, and visualizes SOL transfers as connections between nodes.

Features:
---------
- Input a token address to load token data and visualize token holders.
- Display SOL transfer relationships among top token holders.
- Search for a specific wallet address and zoom into its node.
- View wallet details via a modal popup.
- Export the current visualization to a PDF using html2canvas and jsPDF.
- Footer includes text links to "web | x | discord" with relevant hyperlinks.

How to Use:
-----------
1. Enter a valid token address in the "Token Address" field and click "Load".
2. Wait while the data is fetched and the visualization is built.
3. Use the "Wallet Address" search field to locate a specific wallet.
4. Click on any node to view wallet details.
5. Click "Download PDF" to save the visualization as a PDF.

Dependencies:
-------------
- D3.js (v7)
- Solana Web3.js (latest version via unpkg)
- html2canvas (v1.4.1)
- jsPDF (v2.5.1)

Configuration:
--------------
- The project uses Helius RPC endpoint with an API key. Change the API key in the connection URL if needed.
