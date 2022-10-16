# Style-Transfer
Style transfer using pretrained vgg19 model 

## To change the resulting image, change the content and style image

```
# load in content and style image
content = load_image('images/your_content_image').to(device)
# Resize style to match content, makes code easier
style = load_image('images/your_style_image', shape=content.shape[-2:]).to(device)
```

## To add your own images for style transfer, add those images to the images folder

## Some resulting images:


<img width="1142" alt="Screen Shot 2022-10-16 at 4 52 09 PM" src="https://user-images.githubusercontent.com/49649026/196058134-bd7255f7-629c-4817-8ea0-ca53b16ccb13.png">
<img width="2282" alt="Screen Shot 2022-10-16 at 5 02 24 PM" src="https://user-images.githubusercontent.com/49649026/196058156-0f5d4968-d80d-4c45-bcfa-b56b5c306679.png">
