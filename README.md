# Building LLMs from Scratch

## Google Colab for those who don't have a GPU: https://colab.research.google.com/drive/1_7TNpEEl8xjHlr9JzKbK5AuDKXwAkHqj?usp=sharing

Dependencies (assuming windows): `pip install pylzma numpy ipykernel jupyter torch --index-url https://download.pytorch.org/whl/cu118`

If you don't have an NVIDIA GPU, then the `device` parameter will default to `'cpu'` since `device = 'cuda' if torch.cuda.is_available() else 'cpu'`. If device is defaulting to `'cpu'` that is fine, you will just experience slower runtimes.

## Visual Studio 2022 (for lzma compression algo) - https://visualstudio.microsoft.com/downloads/

## OpenWebText Download - https://skylion007.github.io/OpenWebTextCorpus/

[Create a Large Language Model from Scratch with Python](https://www.youtube.com/watch?v=UU1WVnMk4E8)
