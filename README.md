# Bounding-Box-Creation

This Python code uses OpenCV and Matplotlib to load an image, draw a green rectangular bounding box on it, and display the result. It begins by reading a sample image file named 0001.jpeg using OpenCV. A bounding box is defined by specifying the top-left and bottom-right coordinates. The cv2.rectangle function is then used to draw this box on the image with a green color and a thickness of 2 pixels. Since OpenCV loads images in BGR format and Matplotlib expects RGB, the color channels are converted before displaying the final image using plt.imshow().








