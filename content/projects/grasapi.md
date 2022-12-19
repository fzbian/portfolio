+++
author = "fzbian"
title = "Grasapi"
date = "2022-12-13"
description = "Meme generator returns an image with the parameters indicated in the URL, perfect for use as an API."
tags = [
    "api",
    "golang",
]
+++

[Website](https://grasapi.fzbian.me/) | [Suggest Meme](https://mhht913wjms.typeform.com/to/DQD2Fak9) | [Contact](mailto:email@example.com)

An API (Application Programming Interface) is a set of protocols, tools and definitions that enable communication between different systems or applications. An API provides a way to access the data and functionalities of a system or application in a controlled and secure way, allowing other applications or systems to integrate and use those data and functionalities in a simple way.

GrasAPI is an API that provides access to a large database of memes. You can access GrasAPI memes by a simple request and apply different parameters to filter the memes you want to see. This makes it very easy and fast to access a wide variety of memes and use them in your projects or applications.

Go (language in which the API is made) is a programming language developed by Google. It is a general purpose language, which means that it can be used to create applications of any type, from desktop applications to web and mobile applications. Go stands out for its simplicity, performance and security, which makes it very popular among developers.

Echo (framework in which the API is built) is a framework for creating web applications in Go. It offers a set of tools and functionalities that make it easy to create web applications quickly and easily. Echo includes a high-performance network middleware, an easy-to-use routing system and many other useful features to create web applications efficiently.

## Example

Input

`
  GET https://grasapi.fzbian.me/api/trump/?text=go%20is%20the%20best%20programming%20language
`

Output

![](https://grasapi.fzbian.me/api/trump/?text=go%20is%20the%20best%20programming%20language)

## Templates

| ID                          | Preview                                                                                                                      | Params                          |
|:----------------------------|:-----------------------------------------------------------------------------------------------------------------------------|:--------------------------------|
| `change_my_mind`            | [change_my_mind](https://github.com/fzbian/meme-generator/blob/main/memes/change_my_mind.png?raw=true)                       | `text`                          |
| `disappointed_black_guy`    | [disappointed_black_guy](https://github.com/fzbian/meme-generator/blob/main/memes/disappointed_black_guy.png?raw=true)       | `text1`, `text2`                |
| `distracted_boyfriend`      | [distracted_boyfriend](https://github.com/fzbian/meme-generator/blob/main/memes/distracted_boyfriend.png?raw=true)           | `text1`, `text2`, `text3`       |
| `drake`                     | [drake](https://github.com/fzbian/meme-generator/blob/main/memes/drake.png?raw=true)                                         | `text1`, `text2`                |
| `expanding_brain`           | [expanding_brain](https://github.com/fzbian/meme-generator/blob/main/memes/expanding_brain.png?raw=true)                     | `text1`, `text2`, `text3`, `text4` |
| `jason_momoa_henry_cavil`   | [jason_momoa_henry_cavil](https://github.com/fzbian/meme-generator/blob/main/memes/jason_momoa_henry_cavil.png?raw=true)     | `text1`, `text2`                |
| `left_right`                | [left_right](https://github.com/fzbian/meme-generator/blob/main/memes/left_right.png?raw=true)                               | `text1`, `text2`                |
| `running_away_balloon`      | [running_away_balloon](https://github.com/fzbian/meme-generator/blob/main/memes/running_away_balloon.png?raw=true)           | `text1`, `text2`, `text3`       |
| `spiderman`                 | [spiderman](https://github.com/fzbian/meme-generator/blob/main/memes/spiderman.png?raw=true)                                 | `text1`, `text2`                |
| `this_is`                   | [this_is](https://github.com/fzbian/meme-generator/blob/main/memes/this_is.png?raw=true)                                     | `url`                           |
| `three_headed_dragon`       | [three_headed_dragon](https://github.com/fzbian/meme-generator/blob/main/memes/three_headed_dragon.png?raw=true)             | `text1`, `text2`, `text3`       |
| `undertaker`                | [undertaker](https://github.com/fzbian/meme-generator/blob/main/memes/undertaker.png?raw=true)                               | `text1`, `text2`                |
| `grim_reaper_knocking_door` | [grim_reaper_knocking_door](https://github.com/fzbian/meme-generator/blob/main/memes/grim_reaper_knocking_door.png?raw=true) | `url1`, `url2`, `url3`, `url4`  |
| `zoolander`                 | [zoolander](https://github.com/fzbian/meme-generator/blob/main/memes/zoolander.png?raw=true)                 | `text1`, `text2` |
