**Multi-Input Model**

The Omniglot dataset is used, which has the inputs:

  1. Image data
  2. Alphabet data (in One-hot encoded vector format)

The two separate networks that handle these inputs are concatenated by `torch.cat( (x_image, x_alphabet), dim =1 )`

The predicted output is a character. 
