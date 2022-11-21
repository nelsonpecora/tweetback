# `tweetback` Twitter Archive for `@nelsonpecora`

This is an archive of my twitter account, available at `tweet.nelson.codes`. Anything after October 2022 has been crossposted to Mastodon at [`@nelson@mainframe.club`](https://mainframe.club/@nelson)

[Original tweetback project](https://github.com/tweetback/tweetback)

## Instructions for updating

If I have a new archive: `yarn run import`

Run `yarn start` to test it locally. To deploy, push to Github.
### Fetch additional tweets from the API

1. Get the `TWITTER_BEARER_TOKEN` (note to future self: it's in 1pass) and put it in your env: `export TWITTER_BEARER_TOKEN=`
2. Run `yarn fetch-new-data`
