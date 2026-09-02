# GTFS Feeds

This repository contains the following GTFS Schedule feeds maintained by me.

## List

### Hungary

#### Funicular

[`hu_funicular`](hu_funicular)

#### Chairlift

[`hu_chairlift`](hu_chairlift)

#### Lake Balaton ferry

[`hu_bahart-ferry`](hu_bahart-ferry)

#### Üröm

[`hu_urom`](hu_urom)

Many thanks to the team of [menetrend.app](https://menetrend.app) for helping to create the first version of the feed!

#### Dunakeszi ferry

[`hu_dunakeszi-ferry`](hu_dunakeszi-ferry)

#### Pásztor ferry (Szentendre)

[`hu_pasztor-ferry`](hu_pasztor-ferry)

## Deployment

On pushes to `main`, all changed feeds are zipped and uploaded to my public [AWS S3 bucket](s3://gtfs-gy-mate/).
See their HTTPS permalinks at [gy-mate.hu/gtfs](https://gy-mate.hu/gtfs).

## License

Data in this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See [`license.txt`](license.txt) for its full text.
