### An exploratory analysis of some datasets of Buenos Aires City.

void invertir_rango(vector<int>& v, int i, int j)
Pre: 0 ≤ i < |v| ∧ 0 ≤ j < |v| ∧ v = v0
Post: (∀k : int) (0 ≤ k < min(i, j) ∨ max(i, j) < k < |v| =⇒ (v[k] = v0[k])) ∧ (min(i, j) ≤
k ≤ max(i, j) =⇒ v[k] = v0[min(i, j) + max(i, j) − k])
