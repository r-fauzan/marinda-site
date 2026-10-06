# Marinda & Ilon Ceramics

A mock Hugo website using the existing
[Ananke theme](https://github.com/gohugo-ananke/ananke) as a Hugo module.
The website content is currently in Finnish, with a custom responsive style
and a locally hosted ceramics hero photo.

The hero photo is from [Unsplash](https://images.unsplash.com/photo-1578749556568-bc2c40e68b61)
and is included locally at `static/images/ceramics-studio.jpg`.

## Local preview

Install [Hugo Extended](https://gohugo.io/installation/) and [Go](https://go.dev/dl/).
From the project directory, start the local preview server:

```sh
hugo server
```

Open the URL shown in the terminal (by default,
<http://localhost:1313/>). On the first run, Hugo downloads the Ananke theme
module.

To build the static site into the `public/` directory, run:

```sh
hugo
```
