---
toc: true
layout: post
description: James's example markdown post
categories: [markdown]
title: James's Markdown Post
---
# James's Markdown Post

## Hello World

Hello world welcome my name is James and welcome to my markdown post.

`2022-08-24-filename.md`

The year is 2022 the month is Agust and it is the 24th of Agust.

My name is James and I am a student in Mr. Mortensons APCSP class. Next you will learn a little bit more about me
## About me

Hi my name is James Armstrong and I am a student in Mr.Mortensons APCSP class period 3. I play football, am a big movie an tv guy, and some of my favorite sports teams are the Vikings, Timberwolves, and Padres.

---

## Continue to learn about me

Things I like to do:

- Watch tv (Walking Dead and Game of thrones)
- Watch movies
- Play videogames
- Go to practice and play in games
- Watch sports

My Top 5 Movies:

1. Amercian Phsyco
2. Bohenmion Rhapsody
3. Toy Story
4. Halloween(2018)
5. The Hangover

## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

## Images

![]({{ site.baseurl }}/images/logo.png "fast.ai's logo")

## Code

You can format text and code per usual 

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

Formatting text as shell commands:

```shell
echo "hello world"
./some_script.sh --option "value"
wget https://example.com/cat_photo1.png
```

Formatting text as YAML:

```yaml
key: value
- another_key: "another value"
```


## Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |


## Tweetcards

{% twitter https://twitter.com/jakevdp/status/1204765621767901185?s=20 %}


## Footnotes



[^1]: This is the footnote.

