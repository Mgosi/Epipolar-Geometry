# Epipolar Geometry
This project is a simple project in Computer Vision to to find the epipolar lines of two images.

1.  Create SIFT images to find the key points of the images.

<p align="center">
  <br><br>
  <img src="sift1.jpg" align = "center" width = 300>
  <figcaption><p align="center">SIFT Image Right</p></figcaption>
</p>

<p align="center">
  <br><br>
  <img src="sift2.jpg" align = "center" width = 300>
  <figcaption><p align="center">SIFT Image Left</p></figcaption>
</p>

2.  We then find KNN Matchings for the images

<p align="center">
  <br><br>
  <img src="matches_knn.jpg" align = "center" width = 450>
  <figcaption><p align="center">KNN Matches</p></figcaption>
</p>

3.  From the matchings, we chose 10 random points and find the Fundamental Matrix.

4.  We then find the Epipolar lines and plot it on the image.
<p align="center">
  <br><br>
  <img src="epi_left.jpg" align = "center" width = 300>
  <figcaption><p align="center">SIFT Image Left</p></figcaption>
</p>

<p align="center">
  <br><br>
  <img src="epi_right.jpg" align = "center" width = 300>
  <figcaption><p align="center">SIFT Image Left</p></figcaption>
</p>
