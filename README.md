# machine-learning-math
Guide to understanding the mathematical and probabilistic notations in machine learning papers

## Symbols
### Comparisons
- `:=` "Is assigned as" (assignment to the left)
- `=:` "Is assigned to" (assignment to the right)
- `~` "Follows the distribution" (e.g. $X \sim \mathcal{N}(0,1)$ means $X$ follows a normal distribution)

### Logic
- `∴` "Therefore"
- `∋`,`s.t.` "Such that" ("under the condition that")
- `⇒` "Implies" (e.g. "raining ⇒ pouring" means "if it’s raining, then it’s pouring")
- `⇐⇒`,`iff` "If and only if" (e.g. "thunder iff lightening" means thunder and lightening imply eachother)
- `∀` "For all" (universal quantifier)
- `∃` "There exists" (existential quantifier)
- `􏰀`,`QED` "End of logical statement"

### Sets
- `⊂` "Is included in" ("this set is a subset of")
- `⊃` "Includes" ("this set has as a subset")
- `∈` "Is in" ("is an element of")
- `∪` "Union" ("take the elements that are in either set"
- `∩` "Intersection" ("take the elements that the two sets have in common")
- `∅` "Null set" ("the set without any elements in it")

## Expressions
- $p_\theta(x)$ – Prior/initial/underlying probability distribution for state $x$ with model parameters $\theta$
- $q_\theta(x)$ – Posterior/updated/predicted probability distribution for state $x$ with model parameters $\theta$
- $p(x|y)$ - Conditional probability distribution of state $x$ given state $y$
- $\mathcal{N}(\mu,\sigma^{2})$ – Normal or Gaussian distribution
