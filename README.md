
## docker build

`docker build -t [your_image_name]:[your_tag_name(option)] .`

## docker run

`cd my-work-dir`

### python インタープリター
`docker run -it --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp [your_image_name]:[your_tag_name(option)]`

### bash


`docker run -it --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp [your_image_name]:[your_tag_name(option)] /bin/bash`
