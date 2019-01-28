# Docker Build of Ruby on Rails with ReactJS

## Commands to run
If using a new folder name, find and replace `base_ror_build` with the new directory name.

Then run the following:
`docker-compose run web rails new .` and answer `n` to all questions about overwriting.

`docker-compose build`

`docker-compose up`

`docker-compose run web rake db:create`

Checkout the site at `localhost:3000`.

