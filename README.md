# projectlibre-snap

This is the `snapcraft.yaml` file to build the snap package of  ProjectLibre.

## How to build the package
Download the latest projectlibre tar.gz from
[Sourceforge](https://sourceforge.net/projects/projectlibre/files/)
into the `download/` directory, then run the command:
```
$ snapcraft
```

The build picks the latest `projectlibre-*.tar.gz` found in `download/`.

## Known Issues
Printing from a java app is not working and printing is disabled.

## Contact Information
If you have a problem with the packaging as a snap don't hesitate to contact
me. If it's an issue with the software itselft please contact the upstream
developer.

Thanks.

