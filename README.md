# Sequence Prediction Algorithms
Comparison of Structured Prediction Algorithms on a Sequence Prediction Problem

## Objectives
I empirically compared three sequence prediction algorithms on a structured prediction problem, [Handwritten OCR](https://ai.stanford.edu/~btaskar/ocr/). I used existing frameworks for [Structured SVM](https://jmlr.org/papers/volume6/tsochantaridis05a/tsochantaridis05a.pdf) and [Conditional Random Fields](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1162&context=cis_papers), and I self-implemented the [Auto-context](http://pages.ucsd.edu/~ztu/publication/cvpr08_autocontext.pdf) algorithm.  

I varied the window size and performed the recognition on the full word level (using the sliding window strategy). I gave a thorough comparison to the methods I adopted in terms of training and testing errors w.r.t. different window sizes. I varied the number of training and testing samples using different splits including 1,000/4,000, 2,500/2,500, and 4,000/1,000. 
