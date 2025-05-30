| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| napi.c | io_uring/io_uring.c | min_t | 1 |
| | io_uring/alloc_cache.c | kmalloc | 1 |
| | io_uring/napi.c | hash_del_rcu | 3 |
| | io_uring/napi.c | ns_to_ktime | 2 |
| | io_uring/napi.c | static_tracking_do_busy_loop | 1 |
| | io_uring/io_uring.c | io_should_wake | 1 |
| | io_uring/napi.c | __io_napi_remove_stale | 1 |
| | io_uring/io_uring.c | io_has_work | 1 |
| | io_uring/napi.c | napi_id_valid | 2 |
| | io_uring/napi.c | io_napi_blocking_busy_loop | 1 |
| | io_uring/napi.c | INIT_LIST_HEAD_RCU | 1 |
| | io_uring/kbuf.c | scoped_guard | 3 |
| | io_uring/napi.c | HASH_BITS | 2 |
| | io_uring/io_uring.c | ktime_add | 1 |
| | io_uring/io_uring.c | io_get_time | 1 |
| | io_uring/napi.c | busy_loop_current_time | 2 |
| | io_uring/cancel.c | spin_lock | 1 |
| | io_uring/napi.c | io_napi_remove_stale | 2 |
| | io_uring/napi.c | io_napi_register_napi | 1 |
| | io_uring/cancel.c | unlikely | 1 |
| | io_uring/alloc_cache.h | kfree | 1 |
| | io_uring/io-wq.c | list_del_rcu | 2 |
| | io_uring/io-wq.c | INIT_LIST_HEAD | 1 |
| | io_uring/napi.c | __io_napi_del_id | 1 |
| | io_uring/napi.c | ktime_sub | 1 |
| | io_uring/napi.c | hash_min | 2 |
| | io_uring/napi.c | hlist_for_each_entry_rcu | 1 |
| | io_uring/napi.c | io_napi_busy_loop_should_end | 1 |
| | io_uring/napi.c | list_is_singular | 1 |
| | io_uring/io_uring.c | WRITE_ONCE | 7 |
| | io_uring/io-wq.c | list_for_each_entry_rcu | 2 |
| | io_uring/napi.c | __io_napi_do_busy_loop | 2 |
| | io_uring/napi.c | ktime_to_us | 2 |
| | io_uring/io-wq.c | signal_pending | 1 |
| | io_uring/io-wq.c | kfree_rcu | 3 |
| | io_uring/napi.c | net_to_ktime | 2 |
| | io_uring/napi.c | __io_napi_add_id | 1 |
| | io_uring/napi.c | dynamic_tracking_do_busy_loop | 1 |
| | io_uring/cancel.c | copy_from_user | 1 |
| | io_uring/napi.c | io_napi_hash_find | 3 |
| | io_uring/io_uring.c | time_after | 2 |
| | io_uring/napi.c | hlist_add_tail_rcu | 1 |
| | io_uring/advise.c | READ_ONCE | 7 |
| | io_uring/io_uring.c | list_empty_careful | 1 |
| | io_uring/io-wq.c | list_add_tail_rcu | 1 |
| | io_uring/cancel.c | spin_unlock | 2 |
| | io_uring/cancel.c | list_for_each_entry | 2 |
| | io_uring/io_uring.c | spin_lock_init | 1 |
| | io_uring/napi.c | napi_busy_loop_rcu | 2 |
| | io_uring/io_uring.c | io_napi_free | 1 |
| | io_uring/napi.c | ktime_after | 1 |
| | io_uring/napi.c | io_napi_busy_loop_timeout | 1 |
| | io_uring/io_uring.c | guard | 3 |
| | io_uring/io_uring.c | copy_to_user | 2 |