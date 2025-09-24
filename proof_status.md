# Proof status

Here's a table:

Package | Proof | Coverage | Status | Notes
--- | --- | --- | --- | ---
string | `memcpy` | 89% | pass | unreach?
string | `memset` | 100% | pass | 
list | `list_init` | 100% | pass | 
list | `list_push` | 100% | pass | 
list | `list_pop`  | 100% | pass | 
list | `list_peek` | 100% | pass |
list | `list_rm`   | 100% | pass | 
bit | bit | 100% | pass |
bitmap | `bitmap_find_nth`     | 100% | pass |
bitmap | `bitmap_find_consec`  | 100% | unwind fail | fixable?
bitmap | `bitmap_count_consec` | 100% | pass |
pt | `pte_ops`         | 100% | pass | arch-specific
pt | `pte_page`        | 100% | pass |
pt | `pte_allocable`   | 100% | pass |
pt | `pt_ops`          | 100% | pass |
pt | `pt_pte_mappable` | 100% | pass |
pt | `pt_get_pte`      | 93% | pass | improvable
pt | `pt_get`          | 93% | pass | improvable
mem0 | `pp_alloc` | 93% | pass | to be revised
mem0 | `mem_alloc_ppages` | 94% | pass |
mem1 | `mem_alloc_pt`   | 100% | pass | improvable?
mem1 | `mem_find_sec`   | 100% | pass | stub
mem1 | `mem_expand_pte` | 71% | pass | unclear
mem1 | `mem_inflate_pt` | 100% | pass |
mem2 | `mem_alloc_vpage` | | |
mem2 | `mem_map`         | | |
mem2 | `mem_alloc_map`   | | |

Missing: `pp_init`, `mem_alloc_page`, `as_init`



