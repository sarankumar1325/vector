The `file` and `kubernetes_logs` sources now do one final read pass over the files they are watching when shutdown arrives while they are idle, so lines written just before shutdown are no longer dropped.

authors: sarankumar1325
