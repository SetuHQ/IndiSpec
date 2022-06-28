# UNISpec

### Bank on-boarding v0.6.0
A bank-agnostic API spec for on-boarding an user for any financial product.

---

#### How to use

#### Global patterns
- Entities as atomic as possible
- Different entities are linked using `ref_id`s, back to their parent
- Rupee values are in paise, to avoid rounding and currency conversion errors
- Array keys are in plural
- Booleans always begin with `is`, `was`, `has`, `are` etc
- Just one level of nesting

[CHANGELOG](CHANGELOG.md)
