# parallel-distributed-computing-Optimal-Image-Preprocessing

The objective of this assignment is to provide hands-on experience with parallel and
distributed computing using OpenCL by converting a dataset of colored images of skin
lesions into greyscale images.

Problem Description:
You are provided with a dataset of colored images of skin lesions in various JPEG format.
The task is to convert these colored images to grayscale images using OpenCL parallel
computing.

OpenCL Implementation:
Write OpenCL kernels to perform the conversion of colored images to grayscale
images. Ensure that your kernels can handle images of varying sizes. Implement efficient
memory allocation and data transfer strategies for optimal performance.
Image Processing:
Load each colored image from the dataset into memory. Apply the OpenCL kernel to
convert the colored image to greyscale. Save the resulting greyscale images to the disk.

Greyscale conversion involves transforming each pixel of the image from its RGB (Red,
Green, Blue) representation to a single intensity value representing the luminance.

