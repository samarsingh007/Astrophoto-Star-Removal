<hr>

This project is a neural network that can remove stars from images in one simple step leaving only background.

More technically it is a convolutional residual net with encoder-decoder architecture and with L1, Adversarial and Perceptual losses.

**Small example:**

<div align="center">
  <img src="https://github.com/nekitmm/starnet/blob/master/for_git/1.jpg"><br><br>
</div>

<center><h1>Intro</h1></center>

Star removal using classical methods is a very tricky and painful multi-step procedure, which is hard to master
and hard to get nice results from, especially in case of images busy with stars.

This neural net will remove most of stars from input image in one step, leaving only really huge ones, and leaving (well, hopefully)
intact all other small bright things whose shape is significantly different from that of a typical star, like small spiral
galaxies, fine details in nebulosity, HH objects, etc.

It is intended to be used by astrophotographers. Primary use is for background nebulosity enhancement in rich star fields,
but it can also help in creation of nice starless image.