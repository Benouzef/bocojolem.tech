---
title: 'A way to add categories...'
excerpt: 'How to add categories on a Next blog'
coverImage: '/assets/blog/cozies-tone-BO1JWLOUJVc-unsplash.jpg'
date: '2020-07-02T12:51:52Z'
category: 'Nextjs'
author:
  name: Benoit
  picture: '/assets/blog/authors/benouzef.jpeg'
ogImage:
  url: '/assets/blog/cozies-tone-BO1JWLOUJVc-unsplash.jpg'
---


Well I googled it and found this : (https://stackoverflow.com/questions/62049530/nested-routing-in-next-js)

I have to have a deeper and second look though but this seems to be the solution I was looking for...

From what I understood, I should structure things this way 

```
* pages
    * categories 
        * index.js  // A 
        * [categoryId]
            * articles
                * index.js // B 
                * [articleId].js
```

A => to show a list of categories

B => to show list of articles for a specific category

I "just" need to do it now...

<span>Photo by <a href="https://unsplash.com/@coziestone?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Cozies Tone</a> on <a href="https://unsplash.com/t/nature?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

