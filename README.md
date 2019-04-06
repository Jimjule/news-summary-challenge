# Installation & Tests

Clone this repo
Type `http-server` in console
Go to `localhost:8080` on your browser

You can then check tests in the browser console, either by opening dev tools or right clicking the page and then clicking Inspect


# Technologies

- http-server (Node)
- Guardian API
- Javascript
- HTML & CSS
- No libraries or frameworks for a challenge

## Project overview

-----

## User Stories

beforeEach('As a busy politician');

```
    I can see all of today's headlines in one place
    So I know what the big stories of the day are
```

```
    I can click a link to see the original news article
    So that I can get an in depth understanding of a very important story
```

```
    I can see a summary of a news article
    So I can get a few more details about an important story
```

```
    I can see a picture to illustrate each news article when I browse headlines
    So that I have something nice to look at
```

```
    I can read the site comfortably on my phone
    Just in case my laptop breaks
```

```
    I can see whizzy animations in the app
    To make my news reading more fun
```

# MVP

Based on the user stories, I have the following requirements:

  Minimum

  - There is a single page
  - The page displays a headline
  - The headline is fed from an API
  - A headline contains a clickable link

  Functionality

  - The page displays multiple headlines
  - Each article has a summary
  - Each article has a picture
  - It works well on phones (responsive design)

  I have nothing but time

  - Animations to make it fun

# Progress

I have achieved all of the Minimum requirements, as well as the first of the Functionality ones.

## Mockups

### Headlines page

![Headlines page mockup](/images/news-summary-project-headlines-page-mockup.png)

### Article summary page

![Article page mockup](/images/news-summary-project-article-page-mockup.png)

## Resources

* [Guardian newspaper API homepage](http://open-platform.theguardian.com/documentation/)
* [Aylien text summary API docs](http://docs.aylien.com/docs/summarize)
* cURL [man page](https://curl.haxx.se/docs/manpage.html)
* [Hurl](https://www.hurl.it/), a web interface for sending HTTP requests
