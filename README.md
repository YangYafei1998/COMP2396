# Tiancai Server Beta

## Local set up

- Ask a teammate to send you a .env.dev file and copy .env.dev to the project folder.
- Install nvm and yarn (reference: https://gist.github.com/nijicha/e5615548181676873118df79953cb709)
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
