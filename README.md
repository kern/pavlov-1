<p align="center"><img src="https://raw.githubusercontent.com/dsys/pavlov/master/resources/logo.png" alt="logo" width="480" /></p>

A state-of-the-art content moderation service

## Screenshots

<img src="https://raw.githubusercontent.com/dsys/pavlov/master/resources/pavlov-screen-1.png" alt="Pavlov screenshot 1"/>

<img src="https://raw.githubusercontent.com/dsys/pavlov/master/resources/pavlov-screen-2.png" alt="Pavlov screenshot 2"/>

## Development

Take a look at the [docker-compose configuration file](https://github.com/dsys/pavlov/blob/master/docker-compose.yaml) to run the provided services:

    $ docker-compose up -d pavlov

You'll want to migrate the database and initialize the elasticsearch cluster locally. You can find information about how to do that in `src/migrations` and `src/elasticsearch` respectively.

*Better documentation coming soon!*

## License

Apache 2.0
