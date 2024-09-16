<a href="https://www.buymeacoffee.com/outofai" target="_blank"><img src="https://img.shields.io/badge/-buy_me_a%C2%A0coffee-red?logo=buy-me-a-coffee" alt="Buy Me A Coffee"></a>
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Ashleigh%20Watson)](https://twitter.com/OutofAi) 
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Alex%20Nasa)](https://twitter.com/banterless_ai)

# Google Colab Usage:

For T4 GPU
```
!curl -L "https://github.com/OutofAi/tiny-cuda-nn-wheels/releases/download/1.7.2/tinycudann-1.7.post75240121-cp310-cp310-linux_x86_64.whl" -o tinycudann-1.7.post75240121-cp310-cp310-linux_x86_64.whl
!pip install tinycudann-1.7.post75240121-cp310-cp310-linux_x86_64.whl --force-reinstall
import tinycudann as tcnn
```

For A100 GPU and L4 GPU
```
!curl -L "https://github.com/OutofAi/tiny-cuda-nn-wheels/releases/download/1.7.2/tinycudann-1.7.post89240121-cp310-cp310-linux_x86_64.whl" -o tinycudann-1.7.post89240121-cp310-cp310-linux_x86_64.whl
!pip install tinycudann-1.7.post89240121-cp310-cp310-linux_x86_64.whl --force-reinstall
import tinycudann as tcnn
```

