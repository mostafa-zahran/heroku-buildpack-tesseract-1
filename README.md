# Heroku Buildpack Tesseract

This package provide a custom Heroku buildpack providing the [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) binary and all the required libraries to Heroku apps. Training data for English And Arabic languages is provided. 

## Configuration

1. setup your app as  
    ```
    heroku buildpacks:set heroku/LANG
    heroku buildpacks:add https://github.com/mostafa-zahran/heroku-buildpack-tesseract-1
    ```
	
    where `LANG` is the language used by your app (e.g., `ruby`, `python`, or `nodejs`). A complete list of Heroku buildpacks can be found [here](https://devcenter.heroku.com/articles/buildpacks).
2. you can use the `tesseract` binary in your Heroku app!
3. deploy :)

## Note
This is a modified fork from https://github.com/oswellchan/heroku-buildpack-tesseract
This fork upgrades Tesseract binary version from 3.03 to 3.04.01

## License
MIT License.

Original work Copyright (c) 2013 Marco Azimonti  
Modified work Copyright (c) 2015 Matteo Maggioni  
Modified work Copyright (c) 2017 Oswell Chan
