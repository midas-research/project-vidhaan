A novel dataset for benchmarking citation worthiness detection task in the American Legal Corpus. For more details about the dataset please refer to the original paper.


### Data Fields

- **File Name**: the case file to which the sentence belongs.
- **Sentence Number**: The sentence number as present in the document.
- **Sentence**: The naturally occurring sentence in the text (after preprocessing/removing citation span.)
- **Label**: Integer value of ‘0’ or ‘1’. ‘0’ represents that the sentence is not citation worthy whereas ‘1’ represents that the sentence is citation worthy.


### Data Splits

|Split| #datapoints  |
|--|--|
| Train-Small | 800,000 |
| Validation-Small | 100,000 |
| Test-Small | 100,000 |
| Train-Medium | 8,000,000 |
| Validation-Medium | 1,000,000 |
| Test-Medium | 1,000,000 |
| Train-Large | 142,588,927 |
| Validation-Large | 17,934,940 |
| Test-Large | 17,935,336 |


### Small Dataset

```python
from datasets import load_dataset

# get small dataset
dataset = load_dataset("Vidhaan/LegalCitationWorthiness", "small")
```

### Medium Dataset

```python
from datasets import load_dataset

# get medium dataset
dataset = load_dataset("Vidhaan/LegalCitationWorthiness", "medium")
```

### Large Dataset

```python
from datasets import load_dataset

# get large dataset
dataset = load_dataset("Vidhaan/LegalCitationWorthiness", "large")
```

## Citation Information


## Contributions
Thanks to [@PritishWadhwa](https://github.com/PritishWadhwa), [@gitongithub](https://github.com/gitongithub), [@dhumketu](https://github.com/dhumketu) for adding this dataset
