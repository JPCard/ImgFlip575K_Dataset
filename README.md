# Memes Dataset

[About](#About) | [Memes Dataset](#memes-dataset) | [How to run](#how-to-run)

## About

Scraped top 100 popular memes from **[Imgflip](https://imgflip.com/)** using **[Scrapy](https://docs.scrapy.org/en/latest/)**

A bigger version of **[Imgflip top 24 memes](https://www.kaggle.com/dylanwenzlau/imgflip-meme-text-samples-for-top-24-memes)**

Total memes - **574701**

Can be used with **[Imgflip API](https://api.imgflip.com/)**

## Memes Dataset

Top 100 popular memes ```./dataset/popular_100_memes.csv```

Nr of memes / template ```./dataset/statistics.json```

- Templates ```./dataset/templates```

Template Example
```yaml
{
  "title": "10 Guy Meme Template",
  "template_url": "https://imgflip.com/s/meme/10-Guy.jpg",
  "alternative_names": "Really High Guy, Stoner Stanley, Brainwashed Bob, stoned guy, ten guy, stoned buzzed high dude bro",
  "template_id": "101440",
  "format": "jpg",
  "dimensions": "500x454 px",
  "file_size": "24 KB"
}
```

- Memes ```./dataset/memes```
  
  Meme example:
```yaml
{
    "url": "https://i.imgflip.com/3pxtz2.jpg",
    "post": "https://imgflip.com/i/3pxtz2",
    "metadata":{
      "views": "1,335",
      "img-votes": "1,335",
      "title": "Yo Dawg Heard You",
      "author": "Trouble869"
    },
    "boxes": [
      "WHEN YOU'RE HAVING A BAD DAY",
      "BUT THEN YOU FIND OUT WHO YOUR EX IS DATING NOW"
    ]
  }
```


## How to run
The dataset is already scraped in ./dataset

If you need fresh memes, just do:
```sh
$> cd project
```
```sh
$> pip install
```
```sh
$> run.sh 
```
