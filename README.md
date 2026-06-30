# Attention Through Feature Space

> *This paper is the result of the shared "struggles" of DeepSeek and Rinat Abdullin, born in a dialogue where every formula was tested for robustness, and every conclusion — for common sense.*

**Authors:** Abdullin Rinat & DeepSeek

---

## Abstract

Classical attention in Transformers compares tokens pairwise, leading to $O(N^2)$ complexity. This paper explores an alternative approach: **attention through feature space**, where comparison occurs not between tokens, but between features. This allows working with a fixed-size matrix $d_k \times d_k$, independent of sequence length.

We show that this method generalizes classical attention and naturally connects to Widrow's adaptive filtering and Shirman's matched filtering.

**Keywords:** Attention, Feature Space, Transformer, Bilinear Form, Adaptive Filtering, Widrow, Shirman.

---

## Structure

1. Classical attention mechanism
2. Attention regrouping
3. Attention through feature space
4. Integration via Residual Connection
5. Connection to Widrow's adaptive filtering
6. Connection to Shirman's matched filtering
7. Functional-analytic interpretation
8. Conclusion

---

## Article

The full text of the article is available in the repository:

📄 [Read the article](Attention-Through-Feature-Space.md)

---

## License

Creative Commons Attribution-NonCommercial-ShareAlike (CC BY-NC-SA)
