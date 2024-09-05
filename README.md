**Local Deployment Instructions**
**Node**
1)Go to the Node website and download the Long Term Support version of node (left side button should say something like 16.x.x LTS:
https://nodejs.org/en/

**DFX**
2)Open up your Terminal app (In your applications folder). Or just search for it with spotlight.
3)Copy the following command and paste it into your terminal
DFX_VERSION=0.9.3 sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)"

**Clone the Repository**
4) Navigate to the repo using the terminal/command line and run npm i (keep in mind that the package.json does have dated modules, do not run npm audit fix)
5)  Split the terminal at this position
6)type dfx start in one terminal
7) In the parallel terminal type dfx deploy and then type npm start

8) Open your browser and type localhost:8080 and view the webpage
