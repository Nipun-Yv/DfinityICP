**Smart Contract Candid UI Interaction Link**<br/>
https://a4gq6-oaaaa-aaaab-qaa4q-cai.raw.ic0.app/?id=7x4z2-naaaa-aaaap-qhwnq-cai
<br/>
This will let you interract with the canister(Smart Contract)<br/>
**Local Deployment Instructions**
**Node**
<br/>
1)Go to the Node website and download the Long Term Support version of node (left side button should say something like 16.x.x LTS or above:
https://nodejs.org/en/ <br/>


**DFX**<br/>
2)Open up your Terminal app (In your applications folder). Or just search for it with spotlight.
<br/>
3)Copy the following command and paste it into your terminal
<br/>
** sudo DFX_VERSION=0.11.2 sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)")**
<br/>
(click on proceed with installation and wait for the dfinity logo)
<br/>
**Clone the Repository**
<br/>
4) Navigate to the repo using the terminal/command line and run npm i (keep in mind that the package.json does have dated modules, do not run npm audit fix)
<br/>
5)  Split the terminal at this position
<br/>
6)type dfx start in one terminal
<br/>
7) In the parallel terminal type dfx deploy and then type npm start
<br/>
8) Open your browser and type localhost:8080 and view the webpage
<br/>
