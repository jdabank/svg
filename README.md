# SVG Walkthrough

SVG (scalable vector graphics) is the image format most commonly used on the web. It is an open standard developed by the World Wide Web Consortium. 

## Vector Images vs. Raster Images

![Vector-v-raster-1024x640-1](https://user-images.githubusercontent.com/102549585/213844991-ba978aad-cfde-42fa-b90d-84af9808a24d.jpg)

A raster image is just pixels at a fixed size. They are not very scalable and zooming in or out makes that obvious!

A vector image is numerical data drawn by your applications into fixed shapes that scale automatically. If you zoom in on a vector image it still looks sharp, and same if you zoom out.

The vast majority of websites use vector graphics for their websites.

## Let's Check it Out!

mkdir vector

cd vector

touch vector.html

Set up your HTML boilerplate and add an <image> tag to the body.

<img width="1024" alt="Screenshot 2023-01-21 at 12 30 15 AM" src="https://user-images.githubusercontent.com/102549585/213845187-25790397-4d0d-4cb7-8224-cc2651badbb0.png">

Go to a Wikipedia page for a company you know. Click on the download icon, and then View in Browser. Copy the link that comes up and insert it into the image tag.

<img width="1024" alt="Screenshot 2023-01-21 at 12 36 06 AM" src="https://user-images.githubusercontent.com/102549585/213845293-681bfa98-6d97-4f0a-a01b-c2c2da4918ba.png">

Give the image a style of "width: 100vh;"

<img width="1024" alt="Screenshot 2023-01-21 at 12 38 38 AM" src="https://user-images.githubusercontent.com/102549585/213845384-d1d05a22-98a9-46a8-8dba-dcbddabd1d3d.png">

Note: 100vh means that it will take up 100% of the viewport.

Now, constantly change the size of your browser window. What happens to the quality of the image?

## Sources for SVG Files
