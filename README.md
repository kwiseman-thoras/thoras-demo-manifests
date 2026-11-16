# Thoras demo manifests

Deployed to a local cluster by the Argo CD Application `shop-demo` (path `manifests/shop`).
`cart-worker`'s PodDisruptionBudget allows no evictions, which is what the Thoras demo fixes with a pull request.
