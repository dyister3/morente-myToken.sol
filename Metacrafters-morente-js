/* 
// Metacrafters - Beginning Javascript
//
// This is a javascript playground for testing your javascript code!
// When you are ready to test, simply right click and select "Run Code"
// to see the result print below. If you have more then one snippet of code,
// you can highlight the code you want to test, and then right click and select "Run Code"
//
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
const NFTs = []

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (_playername, _position, _jerseynum, _yearsplayed) {
const NFT = {
   "playername": _playername,
   "position": _position,
   "jerseynum": _jerseynum,
   "yearsplayed": _yearsplayed,
   }
   NFTs.push(NFT);
   console.log("Minted: " + _playername);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
for(let i = 0; i < NFTs.length; i++){
   console.log("\nID: \t\t" + (i + 1));
   console.log("Player Name: \t\t" + NFTs[i].playername);
   console.log("Position: \t" + NFTs[i].position);
   console.log("Jersey Number: \t" + NFTs[i].jerseynum);
   console.log("Years played: \t\t" + NFTs[i].yearsplayed);
}
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
console.log("\n" + NFTs.length);
}

// call your functions below this line
mintNFT("Michael Jordan", "23", "Shooting Guard", "15"),
mintNFT("Kobe Bryant", "8/24", "Shooting Guard", "20"),
mintNFT("Tracy McGrady", "1", "Shooting Guard", "15"),
mintNFT("Dwayne Wade", "3/9", "Shooting Guard", "16"),
listNFTs();
getTotalSupply();
