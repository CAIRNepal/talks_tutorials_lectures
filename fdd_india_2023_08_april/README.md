# Applications of Advanced/Deep Neural Networks in Knowledge Graphs Construction
***

## Events Description

<img src="https://user-images.githubusercontent.com/52251022/230404834-1c77fc86-cf5c-4bda-9f2e-d0f29fc10051.jpg" alt="event" width="400px"/>

## Software/Libraries 
- `fastcoref`
- `spacy` and download spacy model, e.g., `en_core_web_sm`
- `flair` 
- `stanford_openie` 
- `transformers` 
- `torch_geometric` 
- `torch`
- `streamlit`
- `streamlit-agraph`

## Related Papers
- Akbik, A., Bergmann, T., Blythe, D., Rasul, K., Schweter, S. and Vollgraf, R., 2019, June. FLAIR: An easy-to-use framework for state-of-the-art NLP. In Proceedings of the 2019 conference of the North American chapter of the association for computational linguistics (demonstrations) (pp. 54-59).
- Otmazgin, S., Cattan, A. and Goldberg, Y., 2022. F-COREF: Fast, Accurate and Easy to Use Coreference Resolution. arXiv preprint arXiv:2209.04280.
- Angeli, G., Premkumar, M.J.J. and Manning, C.D., 2015, July. Leveraging linguistic structure for open domain information extraction. In Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 1: Long Papers) (pp. 344-354).
- Cabot, P.L.H. and Navigli, R., 2021, November. REBEL: Relation extraction by end-to-end language generation. In Findings of the Association for Computational Linguistics: EMNLP 2021 (pp. 2370-2381).
## Debugging
If you get any errors about `torch_scatter version_cuda.so: undefined symbol` error then please make sure that you have installed the following:
- PyTorch
- [Torch geometric](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html)

Further, make sure your installation of `torch_geometric` is compatible with your `PyTorch` installation.

For `Spacy` if you are getting any error (or issues) due to the content/directory that has start with `~` then you can go to the directory that is pointed out during at the error and delete them. Anything that starts with `~` can be safely deleted. Ideally this directory or files that start with `~` should be inside python installation directory like `../sites/packages..`.


## `Warning!: In Linux and other Unix based systems ~ represents the home directory. So be careful before executing the remove command.`


