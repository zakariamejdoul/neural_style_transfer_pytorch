# Build a Neural Style Transfer with PyTorch

## Notes
The `requirements.txt` file should list all Python libraries that our models depends on, and they will be installed using:

```
pip install -r requirements.txt
```

## Behaviour
This project explains how to implement the `Neural Algorithm of Artistic Style` developed by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge. Neural-Style, or Neural-Transfer, allows you to take an image and reproduce it with a new artistic style. The algorithm takes three images, an input image, a content-image, and a style-image, and changes the input to resemble the content of the content-image and the artistic style of the style-image.

![picture alt](static/NTS.png "NTS Diag")