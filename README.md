# GTFS Feeds

This repository contains the following GTFS Schedule feeds maintained by me.

## List

### Hungary

#### Funicular

[`hu_funicular`](hu_funicular)

#### Chairlift

[`hu_chairlift`](hu_chairlift)

#### Üröm

[`hu_urom`](hu_urom)

Many thanks to the team of [menetrend.app](https://menetrend.app) for helping to create the first version of the feed!

## Deployment

On pushes to `main`, all changed feeds are zipped and uploaded to my public [AWS S3 bucket](s3://gtfs-gy-mate/). See their HTTPS permalinks at [gy-mate.hu/gtfs](https://gy-mate.hu/gtfs).
