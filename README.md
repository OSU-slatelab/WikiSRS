# WikiSRS

Similarity and relatedness datasets for Wikipedia entities (WikiSRS). These datasets were developed and
published in the following paper:

- D Newman-Griffis, A M Lai, and E Fosler-Lussier, ["Jointly Embedding Entities and Text with Distant Supervision"](http://drgriffis.github.io/papers/2018-Repl4NLP.pdf).  In _Proceedings of the 3rd Workshop on Representation Learning for NLP (Repl4NLP)_, 2018.

The dataset is provided in the `dataset` folder as two CSVs, where each line gives two Wikipedia page IDs, their surface forms, the mean similarity/relatedness scores assigned by MTurkers, the standard deviation of scores, and the raw scores themselves.

## Demo

The MTurk interface we used for our HITs is in the `interface` folder, or you can see live demos here:

- [Relatedness interface demo](https://slate.cse.ohio-state.edu/WikiSRS/interface/relatedness.html)
- [Similarity interface demo](https://slate.cse.ohio-state.edu/WikiSRS/interface/similarity.html)

We have also provided the original CSV files we used in MTurk for generating our HITs, in the `mturk_datafiles` folder.

## Reference

If you use this dataset in your own work, please cite the paper above:

```
@inproceedings{Newman-Griffis2018Repl4NLP,
  author = {Newman-Griffis, Denis and Lai, Albert M. and Fosler-Lussier, Eric},
  title = {Jointly Embedding Entities and Text with Distant Supervision}, 
  booktitle = {Proceedings of the 3rd Workshop on Representation Learning for NLP (Repl4NLP)},
  year = {2018}
}
```
