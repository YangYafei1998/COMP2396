# Tiancai Server Beta - local set up

## Set development environment 

- Ask a teammate to send you a .env.dev file and copy .env.dev to the project folder.

## Installation

- Make sure you have `npm` and `node` installed (reference: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).
- Install nvm and yarn (reference: https://gist.github.com/nijicha/e5615548181676873118df79953cb709).
- Change the version of node to 11 `nvm use 11`.
- Install the dependencies using `npm install --dev`.

## Database 

- Create a postgres 9.4 docker container.
- Set `POSTGRES_URI` in .env.dev according to container's access URL.
- Create `TIANCAI` dastabase in postgres using TablePlus.



- Install the dependencies using `npm install --dev`.
- Create a postgres 9.4 docker container, and expose the port configured in your .env.dev.
- Create `TIANCAI` dastabase in postgres using TablePlus.
- Run `npm run dev` or `yarn dev`.
- Api runs on localhost:1337.
- Ask a teammate give you the latest copy of postman collections and try it out. Or go ahead to set up the frontend dashboard and test via the GUI.


#Tiancai Dashboard

## Local set up

- Install dependency `yarn`
- Run `yarn start`.
