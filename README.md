## Comparison to Synthetic Models

We compare three real-world networks (Facebook, Email, Erdős collaboration) with six generative models: **Erdős-Rényi (ER)**, **Watts-Strogatz (WS)**, **Barabási-Albert (BA)**, **Stochastic Block Model (SBM)**, **LFR Benchmark**, and **Forest Fire**.  
Evaluation metrics include **clustering coefficient**, **average path length**, **assortativity**, and **rich-club coefficient**.

### Key Takeaways

- **Erdős-Rényi (ER)**  
  Fails across all datasets. Produces near-zero clustering and no meaningful structure → serves only as a randomness baseline.

- **Watts-Strogatz (WS)**  
  Successfully captures **high clustering** and reasonably short paths, but lacks **hub structure** and rich-club behavior.

- **Barabási-Albert (BA)**  
  Reproduces **short paths** and **hub dominance**, but has **very low clustering**, missing local community structure.

### Advanced Models

- **Stochastic Block Model (SBM)**  
  Best at modeling **community structure and assortativity** (especially Facebook), but underestimates clustering in large, sparse networks.

- **LFR Benchmark**  
  Provides the most realistic **degree + community distributions**. Matches collaboration networks well, but is **computationally expensive** at scale.

- **Forest Fire Model**  
  Most **holistic and consistent** across datasets:
  - High clustering (close to real networks)
  - Strong rich-club behavior
  - Captures densification and social expansion dynamics  

### Conclusion

- **WS → local clustering**
- **BA → global hubs**
- **SBM → community structure**
- **LFR → realistic distributions (but costly)**
- **Forest Fire → best overall approximation**

No single classical model suffices; among all methods, the **Forest Fire model** most closely captures the combined structural properties of real-world networks.