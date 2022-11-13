![cover](./frontend/asset/service.png)
 
<p align="center">
<a target="_blank" href="https://nextjs.org/docs/getting-started"><img src="https://img.shields.io/badge/NextJS-000000.svg?style=for-the-badge&logo=Vercel&labelColor=000"/></a>

</p>
<p align="center">
  This repository contains the <strong>Frontend</strong> source code and files written with <b>NextJS</b> a Javascript Framework that enables <b>React-based</b> web-applications with <b>Server-Side Rendering</b> and genearting <b>Static Websites</b>. The 
  Xtelpt is about Getting mental health care anywhere at anytime at 100% confidentiality.
</p>

<p align="center">
<a href="#introduction">Frameworks and APis</a> &nbsp;&bull;&nbsp;
<a href="#usage">Usage</a> &nbsp;&bull;&nbsp;
<a href="#issue">Issues?</a>&nbsp;&bull;&nbsp;
<a href="#documentation">Lesson and Remarks</a> &nbsp;&bull;&nbsp;
</p>

# Frameworks & API's
This <b>Project</b> was made possible with ```solidity```, ```hardhat```, ```chainlink```, ```quicknode```, ```IPFS```, ```NextJS```, ```HUDDLE01```, ```Polygon```, ```Git```, ```Chai```, ```EtherJS```, and ```Figma```. It's has features such as:

- Creating of user or in this case a client profile.
- Creating of a host or doctors profile.
- Ability for a host to create a meeting and a user to enter the meeting.
- Becoming a volunteer for a campaign.
- Add profile name, pictures, bio and profession.
- A Decentralized WEBRTC for calls.
- Notification.
- Creating Schedules for Hosts.

### LINKS 
[Live Deployed](https://xtelpt-web3-od5fiblal-xprj3ct.vercel.app) <br/>
[Contract](https://mumbai.polygonscan.com/address/0x3C8472f1934f9a09c55041f325aBE528AfCb1388)
> **Note**
> Wallet must be Connected to access any feature.
> Currently on ```Mumbai Faucet```.

## Usage
### How it works for Host:<br/>
- On opening of XTELPT and connecting of wallet, toggle on the host button to become a host while signing up.
- Edit your profile based on your professionalism.
- Set Schedule based on your preferred time and fee.
- Voluteer as a host on campaign(non-paid service)
- Get all meeting schedule on the notification bar, wait for time and click on it and start meeting.

### How Campaign Works:<br/>
- Navigate to campaign at the top bar and click on it.
- Search for specifics campaign or scroll down and click Get Help.
- The system automatically merges you with a Host and a call link will be in your notification.
- click and wait for prompts.

### Incoming Community Feature:<br/>
- xtelpt is enacting a reward gifting system for uncoerced individuals for being in stilt to others and sharing remedies for them in times of need in the community , xtelpt communites will serve as a trestle for mental health awareness programs where individuals can obliterate self-stigmatization, learning from previous experiences and getting to see ratified solutions of near same problem they are facing.


## Issues
- Some of the packages we felt were ```NextJS``` fit for the project were depreciated versions so we had to stress a little in finding other best packages
- Creating a custom room for different peers - With the help of the ```Huddle01``` docs we were able to overcome this challenge by creating a separate roomId prop for best usage.
- Trying to do the custom logic ```Chainlink keepers automation```, which was later swapped out for time based logic automation as it was what we needed.
- Return a mapping in ```solidity```, which I finally resolved to return a struct.
- Verifying my smart contract where I could not paste a code if I import a library as a single file.
- ```Ethers``` as when I reload a page I get "INVALID address ENS name error" which was fixed by properly using the useeffect.

## Lesson and Remarks 
- Proper use of ```for loop``` in ```solidity```.
- Usage of ```keccak256 solidity hashing``` to compare string in ```solidity```.
- Usage of ```EthersJS`` to interact with smart contract which include reading and writing, items like signers and providers.
- Custom hooks in ```NextJS```.
- Keeping track of States and manipulating them to get Best UI flow.
- Creating a Dynamic url in ```NextJs```.
