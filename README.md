# Tamarin

Security protocol analysis with the Tamarin prover: examples, exercises, notes
and formal models.

## Layout

| Folder | Contents |
|---|---|
| `./` | Toy protocol examples (`toy_authentication.spthy`, `fe.spthy`) and study material (slides, dependency-graph notes, manual) |
| `theories/` | Tamarin theories |
| `exercises/` | Practice exercises |
| `halil_denemeler/` | Working notes and experiments |
| `mka/` | MACsec Key Agreement (MKA) formal analysis — models + article |

## mka — MACsec Key Agreement

- `mka/Models/` — evolving MKA protocol models: `MKA.spthy`, `MKA_v1..v10.spthy`
- `mka/article/` — LaTeX article on the formal verification of MKA
  (`main.tex` with `sec1..3`), including the final `MKA_v10.spthy` model
