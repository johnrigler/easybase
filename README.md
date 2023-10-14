<h1> Overview </h1>

Generic Web3 portal for private communication and blockchain data, written to be rendered on IPFS
or your personal server.
This has two parts: 
  a vanilla javascript element that is intended to run on IPFS.
  a server directory with some code that allows generic linux servers to augment the system.

My process is to code on a live *nix server and then migrate into IPFS. The latest IPFS version
is registered into a simple Polygon smart contract.

<h2> Usage </h2>

This emulates a "naked" directory rendered on Apache. The index.php file is linked to index.html
and is written in a way that index.html worked, but index.php will refresh your cache each time 
that it runs. Once the thing is up and running, you can access many visible variables such as the 
'easyBase' object through either the javascript console or the "eval.js" button. This allows you 
to use the system to its fullest capacity on a smart phone. Sadly, the smart phone version still
isn't as easy to navigate as the console. 

<h2> Variations </h2>

I usually build with all libraries local. Because this DOES NOT USE NODEJS, this is not difficult 
to maintain, but I think the Github version frowns on this.
