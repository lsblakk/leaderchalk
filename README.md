# Leaderchalk

Leaderchalk is what writes on Leaderboard


## Requirements

+ Node.js
+ API key for Mozillians.org ([more info](http://mozillians.readthedocs.org/en/latest/api/api.html#getting-an-api-key))

## Usage

1. Add the api key and app name in `lib/keys.js`.
2. (Optional) Edit the country and limit in config.json.
3. Run the app by `./run.sh <YOUR GITHUB USERNAME> <YOUR GITHUB PASSWORD>`.

> You can also setup your github credentials in `index.js` under `GITHUB_USERNAME` and `GITHUB_PASSWORD` variables as well. You, then, need not supply github credentials via the command line. Simply doing `./run.sh` will do the job.
