# EECS504_HW7
Image Translation
In this problem set, we will implement an image-to-image translation method, based on
pix2pix [1]. We hope that this will give you experience reading a modern computer vision
paper and implementing the architecture described within it.
We’ll train a model to generate pictures of facades from label maps, using the CMP Facade
Database [2]. This dataset contains 606 rectified images of facades from various sources, which
have been manually annotated. Below is a sample image from the database. In this homework,
we will implement GAN to translate labels into facade images.
