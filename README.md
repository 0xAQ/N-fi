# N-fi
Polygon **Build it** hackathon submission

## Inspiration
Right Now NFTs are just digital assets with no other use than just holding and resale. But assets in the real world are not like that, you can _mortgage, split( like stocks), exchange it_ etc etc. We wanted NFTs to also be versatile which feels like a real asset.
## What it does
N-fi is in phase one which supports **NFT Mortgage** you can keep your valuable NFTs as collateral and borrow Matic for about _70%_ of the **last sold price**, Later you can repay _90 %_ of the price and retrieve your NFT
## Challenges we ran into
The very first and most difficult one was the _**Approval**_ of NFT, IF we want to _transfer_ an NFT to a smart contract we need to _approve the Smart Contract_ first. But we kept getting errors to approve the smart contract and there was no proper documentation for this. So we just decide to do the transfer via _**Maticjs**_ which approves on its own =)
## Accomplishments that we're proud of
when we started this project we thought it was going to be simple but as we kept building it was getting more and more complex and also time-consuming. So we started staying up late at night, cut our university classes, skipped breakfasts, and stopped watching anime/series so for us completing this project is something we are really proud of 
## How we built it
Our team consists of 3 members, one working on the front-end for design and UI/UX, one working on the smart contract for the mortgage and lending pool and one working on the connection between and front-end and smart contract and also a little bit of DBMS. All the front-end is built with _**reactjs**_  and smart contracts imports were from standard _**OpenZeppelin library**_. A variety of APIs are used for the transfer of NFTs-_**Maticjs**_, getting metadata-_**Alchemy**_, last sold price of an NFT-_**covalent**_. DBMS was written in _**MySQL**_. And finally, All the hosting is done in _**AWS**_ 
## What we learned
Technical wise we learnt many things such as advanced solidity, website hosting, API calls, DBMS and much much more.
Apart From all the technical things. We learnt many things as a team. First and foremost one is
**Work needs to be split**, at the level, we are at now, single-handedly doing both front end and smart contract and also testing is just impossible to complete with the deadline of any hackathon. 
**Proper Communication**, As we are working on different parts of the project and to merge all of these proper communication is 100% needed otherwise the entire code will be riddled with errors!
**BlockChain is so interesting**, We knew we liked creating Dapps and working on blockchain but we didn't expect it to be this awesome like we were so ready to give up anything to finish this project.
## What's next for N-fi
In later stages, we plan on adding a splitter and exchange, a marketplace, a live auction and much more. N-fi is really a big project and as we keep going we might encounter numerous ideas to develop it further. With _NFTs booming in every sector such as real estate, collectables, etc_ **N-fi** is a promising Project
