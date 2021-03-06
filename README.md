# FaceGrab
A tool to collect public images from Facebook and create an image dataset for learning about computer vision applications like gender recognition, and face detection

## Motivation

During an AI class in college, I was learning about computer vision applications such as face detection and gender recognition. I implemented the respective algorithms and wanted to try them out on a new dataset. 

Earlier when Facebook launched their graph API, I came across an API endpoint in Facebook graph search which provides a way to get the full-size profile picture associated with any userid without login/signup. When I contacted Facebook support about this, they responded that all the profile images are public by default. Apparently, Facebook's privacy policy states that all the profile images are in public domain.

Thus I created this tool to collect the public images from Facebook and create a dataset to apply the newly learned vision algorithms. I hope that the tool would be helpful to learners looking for image datasets.

## Usage

```sh
$ python facegrab.py <size of dataset>
```

This will create an image dataset of desired size in the same directory under the facegrab folder.

## Contribute

Want to work on the project? Any kind of contribution is welcome!

Follow these steps:
- Fork the project.
- Create a new branch.
- Make your changes and write tests when practical.
- Commit your changes to the new branch.
- Send a pull request.

## License

[MIT License](https://github.com/ankitaggarwal011/FaceGrab/blob/master/LICENSE)
