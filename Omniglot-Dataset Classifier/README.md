The Omniglot dataset consists of:

  1. Image data
  2. Alphabet data (in One-hot encoded vector format)

The two separate networks that handle these inputs are concatenated by `torch.cat( (x_image, x_alphabet), dim =1 )`
