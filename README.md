A light-weight sentence tokenizer for Korean. 

Half-width punctuation is generally used in Korean, but this tokenizer also supports full-width punctuation. (For details about full-width punctuation in Korean, please see https://www.w3.org/TR/klreq/).

## Installation

pip install kr-sentence


## Sample Code:

```python

from kr_sentence.tokenizer import tokenize

paragraph_str = "저는 미국인이에요. 만나서 반갑습니다."

sentence_list = tokenize(paragraph_str)

for sentence in sentence_list:
	print(sentence)

```

## Other languages

JavaScript -> https://github.com/Rairye/js-sentence-tokenizers
