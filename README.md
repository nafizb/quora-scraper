# Quora Scraper
[![Build Status](https://travis-ci.org/Kaelinator/quora-scraper.svg?branch=master)](https://travis-ci.org/Kaelinator/quora-scraper)

Scrape Quora for a user's statistics and information!
I will try my best to keep up to date on Quora's ever-changing UI!

## Usage
```js
quora('Kael-Kirk')
	.then(console.log)
	.catch((err) => console.log('User not found!'))
```
#### yields
```js
{
  user: 'Kael Kirk',
  picture: 'https://qph.ec.quoracdn.net/main-thumb-110323423-200-xoeyjvjqbxviswiovjvldtobhaywqydo.jpeg',
  credential: '/kāl/ - Runner, developer, creator',
  answers: 66,
  questions: 20,
  posts: 3,
  blogs: 2,
  followers: 45,
  following: 24,
  topics: 70,
  edits: 596,
  totalViews: 42800,
  monthlyViews: 4900
}
```
