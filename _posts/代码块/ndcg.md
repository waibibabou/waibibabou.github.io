```python
import numpy as np

def ndcg(r):
    """
    Compute NDCG (Normalized Discounted Cumulative Gain)
    
    Parameters:
    r (list): Relevance scores in rank order
    
    Returns:
    float: NDCG
    """
    r = np.asarray(r)
    dcg = np.sum(r / np.log2(np.arange(2, len(r) + 2)))
    idcg = np.sum(sorted(r, reverse=True) / np.log2(np.arange(2, len(r) + 2)))
    return dcg / idcg if idcg > 0 else 0

# Example usage
print("NDCG for [3, 2, 1]:", ndcg([3, 2, 1]))

```

```python
#另一种工业界更常用的ndcg计算公式
import numpy as np

def ndcg(r):
    """
    Compute NDCG (Normalized Discounted Cumulative Gain) using 2^relevance - 1
    
    Parameters:
    r (list): Relevance scores in rank order
    
    Returns:
    float: NDCG
    """
    r = np.asarray(r)
    dcg = np.sum((np.power(2, r) - 1) / np.log2(np.arange(2, len(r) + 2)))
    idcg = np.sum((np.power(2, sorted(r, reverse=True)) - 1) / np.log2(np.arange(2, len(r) + 2)))
    return dcg / idcg if idcg > 0 else 0

# Example usage
print("NDCG for [3, 2, 1]:", ndcg([3, 2, 1]))

```

