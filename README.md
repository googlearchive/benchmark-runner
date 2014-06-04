polymer-microtask-timer
=========

Utility only useful for benchmark testing which attempts to figure out, based on timing, when the microtask queue is empty.

WARNING: This component is NOT safe to use in production. In particular, it's method of detecting "empty" isn't robust and it will fail if anyone else is trying to wait on the same condition.
