# [Goal] A long-term direction for VitraeEngine
    $meta:
      color: '#8a40fa'
      roles:
        done: done
    done:
      type: boolean
      description: The task is finished

# [Feature] A self-contained engine capability or system
    $meta:
      color: '#c0b600'
      roles:
        done: done
    done:
      type: boolean
      description: The task is finished

# [Optimization] An improvement in performance of existing features
    $meta:
      color: '#73ff00'
      roles:
        done: done
    done:
      type: boolean
      description: The task is finished

Affected by:
- [Issue] Affects

# [Task] A concrete step towards a feature
    $meta:
      color: '#30a1ce'
      roles:
        done: done
    done:
      type: boolean
      description: The task is finished

Affected by:
- [Issue] Affects

# [Issue] A known design problem in the current code
    $meta:
      color: '#c0392b'
      roles:
        done: done
    done:
      type: boolean
      description: The task is finished

Affects:
- [Feature] Affected by
- [Task] Affected by
