# 📚 Perplexity in Language Models (Simple Notes)

---

## ✅ General Meaning

Perplexity general meaning is = the state of being confused, puzzled, or uncertain.

- **Low perplexity** = model is less confused = better predictions.
- **High perplexity** = model is more confused = worse predictions.

---

## ✅ [Basic Understanding]

**1) Multiplying by less than 1 always shrinks the value**

> Example:
0.9 * 0.9 = 0.81  (less than 0.9)

>0.9 * 0.9 * 0.9 * 0.9 = 0.6561 

(closer to zero)


---

## 2) How an LLM predicts next word probability**

For sentence: *“a red fox”*

P(a red fox) = P(“a”) * P(“red” | “a”) * P(“fox” | “a red”) * P(“.” | “a red fox”)


