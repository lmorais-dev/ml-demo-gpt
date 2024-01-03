# DemoGPT

This is a demo project that I used to apply some knowledge I'm getting about neural networks and machine learning as well
as generative AIs.

I used the tiny shakespeare to train this model.

Don't expect things to make sense, to be accurate or even tidy.

I'm not a Python programmer and I'm still getting used to it as the day of writing this code.

This model runs on about 10 Million parameters. It is extremelly limited and just a proof of concept.

The example image below was run inside `runpod.io` on a community `RTX 6000 Ada` for about 10 minutes.

![example image](/assets/example.png)

A [text example](/example.txt) is also provided. It has a 3k token limit and had it training iterations pumped up to 10k. It is more concise but still outputs random non-sense (that at least looks not so bad).

### Recommendations

PyTorch and NumPy are required to run this. It works on either GPU or CPU.

But you should adjust the parameters to run on the CPU otherwise it will take literally forever.

