# 0.1.4 (unreleased)

* bump lambda rust docker version to 0.1.0-rust-1.27.2
* speed up deployments by ~3.2 seconds by disabling excludeDevDependencies. it's on by default but it's not useful for for Rust focused services

# 0.1.3

* bump lambda rust docker version to 0.1.0-rust-1.27.0

# 0.1.2

* bump lambda rust docker version to 0.1.0-rust-1.26.2
* use a polyfill for fs.copyFileSync to accomidate older versions of node on travis ci

# 0.1.1

* fix exporting plugin

# 0.1.0

* initial release