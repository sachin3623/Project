This is an image captioning project using LSTM and ResNet.Model can generate pretty good captions for a normal picture.But feel free to try it out with any picture you like and share the results you get.

I recommend you to run it on Google Colab because FREE GPUs !!
Just run this python notebook on Colab and in the end try your own image by running these commands

1. !wget img_url
2. apply_model_to_image_raw_bytes(open(img_url, "rb").read())
