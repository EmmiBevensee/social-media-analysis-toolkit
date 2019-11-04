# social-media-analysis-toolkit
Tools I'm developing to analyze social media, particularly hate and disinformation, at scale.

## Link Counter (link_counter.py)
This code takes a list of twitter usernames, iterates over them to find tweets where they shared links, and then sums up the base URLs of everyones links combined and turns it into a matplotlib bar graph. Please check code documentation for usage guidance. The code does take a bit to run depending on your tweet limit and how many accounts you pull. Non-coder friendly hosted version [here](https://colab.research.google.com/drive/1AGgt2Qm2LThNAKeBsnbKRXgWgPc9kFN9).

## Mutuals Detector
Mufos.py uses Twint to detect a given seed accounts mutual followers. It can be incorporated into other more elaborate pipelines for social networks or millieu detection. It is too slow to be useful right now for accounts with massive follower/Following. Here is a [hosted version](https://colab.research.google.com/drive/1AOXQxkOWbq7KEHWVBRiOrYhTOSg3QTqq) that you can open in playground mode to play with.
