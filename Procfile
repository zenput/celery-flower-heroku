web: flower --port=$PORT --broker=$BROKER_URL --max_workers=1000 --max_tasks=2000 --db=$DATABASE_URL --persistent=true --oauth2_key=$FLOWER_OAUTH2_KEY --oauth2_secret=FLOWER_OAUTH2_SECRET --oauth2_redirect_uri=https://staging-flower.herokuapp.com/login --auth_provider=flower.views.auth.GithubLoginHandler

