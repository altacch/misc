# Proof status

Here's a table:

Package | Proof | Coverage | Status | Notes
--- | --- | --- | --- | ---
string | memcpy | 89% | pass | unreach?
string | memset | 100% | pass | 
list | `list_init` | 100% | pass | 
list | `list_push` | 100% | pass | 
list | `list_pop` | 100% | pass | 
list | `list_peek` | 100% | pass |
list | `list_rm` | 100% | pass | 
bit | bit | 100% | pass |
bitmap | `bitmap_find_nth` | 100% | pass |
bitmap | `bitmap_find_consec` | 100% | unwind fail | fixable?
bitmap | `bitmap_count_consec` | 100% | pass |


