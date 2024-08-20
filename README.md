# LLMEmbed: Rethinking Lightweight LLM's Genuine Function in Text Classification
This code is for the LLMEmbed paper accepted in the 62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024)
*https://aclanthology.org/2024.acl-long.433*

## llama2_embedding / bert_embedding / roberta_embedding
The `rep_extract.py` uses language model to extract the representation of `dataset` and saves the representation as `.pt` file.

## MyDataset
`MyDataset.py` reads the representation from `.pt` file.

## DownstreamModel
`DownstreamModel.py` is for the **co-occurence pooling**.

## 📜Citation

This work has been accepted to [ACL-2024](url: https://aclanthology.org/2024.acl-long.433), please cite the paper if you use LLMEmbed or this repository in your research.
Thank you very much 😉

```bibtex
@inproceedings{liu2024llmembed,
    title = "{LLME}mbed: Rethinking Lightweight {LLM}{'}s Genuine Function in Text Classification",
    author = "ChunLiu, ChunLiu  and
      Zhang, Hongguang  and
      Zhao, Kainan  and
      Ju, Xinghai  and
      Yang, Lin",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-long.433",
    pages = "7994--8004",
    }
```
