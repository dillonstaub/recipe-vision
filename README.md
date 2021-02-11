# recipe-vision

A project using computer vision techniques to recognize written and typed recipes. The idea originated because recipes are often scattered across websites, notecards from family & friends, various cookbooks, screenshots, etc.. 

This problem is challenging due to the varied nature of recipe formats. For typed recipes, optical character recognition (OCR) techniques have achieved oustanding results on standard fonts; however, written characters pose a more difficult challenge. 

Tesseract is an open-source OCR engine originally developed by HP and currently maintained by Google (https://en.wikipedia.org/wiki/Tesseract_(software). In Python, pytesseract (https://pypi.org/project/pytesseract/) is a wrapper which allows you to use the Tesseract OCR engine. It provides out-of-the-box functionality for character recognition in images; however, it is not optimized for handwritten character recognition. While it is possible to optimize Tesseract for handwritten character recognition, I opted to take a more flexible, hands-on approach and develop a handwritten classifier using EMNIST data with PyTorch. 

The EMNIST data set was used for handwritten character classification: Cohen, G., Afshar, S., Tapson, J., & van Schaik, A. (2017). EMNIST: an extension of MNIST to handwritten letters. Retrieved from http://arxiv.org/abs/1702.05373 (EMNIST Dataset: https://www.nist.gov/itl/products-and-services/emnist-dataset)

PyTorch was used with the EMNIST data set for handwritten character classification. 
