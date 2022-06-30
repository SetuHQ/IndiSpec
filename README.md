# IndiSpec
## A collection of reference API specifications for various sectors, all tailor-made for India.

---
## Global patterns
- Entities as atomic as possible
- Different entities are linked using `ref_id`s, back to their parent
- Rupee values are in paise, to avoid rounding and currency conversion errors
- Array keys are in plural
- Booleans always begin with `is`, `was`, `has`, `are` etc
- Try for just one level of nesting
- Maintain separate READMEs and CHANGELOGs for each spec

---

## List of specs

### Bank on-boarding v0.6.1
A bank-agnostic API spec for on-boarding an user for any financial product.
