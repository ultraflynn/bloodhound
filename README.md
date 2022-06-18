# bloodhound

A simple tool that takes the downloaded files from Instagram and writes the appropriate EXIF metadata to them.

## Usage
Install golang, clone this repo, create a *data* directory and place your downloaded export (in json format) from Instagram in it. Run the *main.go* and it reads the json file in the content directory and then writes the appropriate file modification and exif data to the image files.
