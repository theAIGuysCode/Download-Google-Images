# Download-Google-Images
Code to mass download images from Google Images using JavaScript Console Window and python script.

Code derived from: https://www.pyimagesearch.com/2017/12/04/how-to-create-a-deep-learning-dataset-using-google-images/

Steps to perform:
- Query your intended Google search
- Scroll down through images until they become unrelated to your query or until you've passed enough images for your dataset
- Right click and hit "Inspect" and then navigate to "Console" tab
- One by one enter the lines from console.js into the console window and run them
- Move urls.txt from Downloads folder to Download-Google-Images folder
- Create an "images" folder where your images will be downloaded
- Run follwing two python commands as follows:
```bash
pip install -r requirements.txt
python download_images.py --urls urls.txt --output images
```

You should now have all your images inside your images folder!
