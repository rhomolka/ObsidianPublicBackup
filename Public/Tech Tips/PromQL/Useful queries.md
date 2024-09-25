    avg without (mode,cpu) (
      1 - rate(node_cpu_seconds_total{mode="idle"}[1m])
    )