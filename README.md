# Plex Meta Manager

This repository contains configuration files for [Plex Meta Manager](https://github.com/meisnate12/Plex-Meta-Manager), a tool for managing metadata in Plex libraries.

## HUGE THANKS TO [TheBigNoob](https://github.com/notryanfraser).  This is almost all of his work.  I added a few things.

## Configuration

The `Movie_posters.yml` file contains configuration for managing movie posters in Plex. The `Movie_collections.yml` file contains configuration for managing movie collections in Plex.

To use these configuration files, make sure to update the `plex` and `tmdb` sections with your own information.

## Usage

To use these configuration files with Plex Meta Manager, run the following command:

```plex_meta_manager.py --config path/to/Movie_posters.yml plex_meta_manager.py --config path/to/Movie_collections.yml```

This will update your Plex library with the metadata specified in the configuration files.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
