# There is prepared docker files for creating ruby on rails application with postgresql db
After cloning you should to create new empty repository and change remotes for new
For create new application need to select what you prefer.
1) Standard rails application with postgresql
[1] docker compose run --no-deps web rails new . --force --database=postgresql
2) Api only application
[2] docker compose run --no-deps web rails new . --api --force --database=postgresql
