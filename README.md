# Github_Trending_Repos

## A REST microservice that lists the languages used by the 100 trending public repos on GitHub. It works by fetching trending repositories by getting the most starred repos created in the last 30 days. It consumes Github's public API : Repositories Search API : [https://docs.github.com/en/rest/reference/search#search-repositories]


### Project is dockerized to be easy integrated with or to be used by internal API Gateway. 


## Installation and run.
```
git clone git@github.com:DevHwary/Github_Trending_Repos.git
cd Github_Trending_Repos/trending_repos/
docker-compose up --build
```

## Run tests
```
docker-compose exec backend sh
python manage.py tests --verbosity=2
```

*Please ignore or remove venv it will not cause any problems*
