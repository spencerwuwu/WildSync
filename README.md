# WildSync

WildSync automatically generates fuzzing harnesses for library APIs by extracting usage patterns in real-world scenarios,
and integrates the usage patterns into existing harnesses to construct new ones covering these functions.

- Read our paper: [link](WildSync_ISSTA25.pdf)
- Benchmark: [link](https://github.com/spencerwuwu/WildSync_issta25)

## Using Wildsync
Installation using the source code in your python environment:
```bash
pip install -r requirements-dev.txt
```
### Run the example
```bash
cd example/ && ./demo.sh
```

## Citing WildSync
```
@article{wu2025wildsync,
  title={WildSync: Automated Fuzzing Harness Synthesis via Wild API Usage Recovery},
  author={Wu, Wei-Cheng and Nagy, Stefan and Hauser, Christophe},
  journal={Proceedings of the ACM on Software Engineering},
  volume={2},
  number={ISSTA},
  pages={963--984},
  year={2025},
  publisher={ACM New York, NY, USA}
}
```
