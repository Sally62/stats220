library(magick)
url <- "https://cdn.pixabay.com/photo/2015/10/08/10/28/education-977454_1280.jpg"

image_read(url) %>%
  image_scale(300)
  meme <- image_read(url)
  meme
image_write(meme, "my_meme.png")
