# mycollege-combined

`docker-compose` file used to build out the entire MyCollege application.

## `.env` File

You must include a `.env` file with the following key-value pairs:

```conf
GITHUB_USERNAME=<GitHub Username>
GITHUB_TOKEN=<GitHub Personal Access Token>
```

**Note**: Please make sure that this `.env` file is never committed into the repository. Treat your personal access token just like you would with your password.
