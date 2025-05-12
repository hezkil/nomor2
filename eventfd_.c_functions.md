| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| eventfd.c | io_uring/eventfd.c | eventfd_signal_allowed | 1 |
| | io_uring/eventfd.c | refcount_dec_and_test | 1 |
| | io_uring/eventfd.c | io_eventfd_grab | 2 |
| | io_uring/cancel.c | io_wq_current_is_worker | 1 |
| | io_uring/eventfd.c | PTR_ERR | 1 |
| | io_uring/eventfd.c | refcount_set | 1 |
| | io_uring/eventfd.c | refcount_inc_not_zero | 1 |
| | io_uring/eventfd.c | lockdep_is_held | 2 |
| | io_uring/eventfd.c | atomic_set | 1 |
| | io_uring/cancel.c | spin_unlock | 2 |
| | io_uring/eventfd.c | rcu_read_lock | 1 |
| | io_uring/eventfd.c | IS_ERR | 1 |
| | io_uring/eventfd.c | __io_eventfd_signal | 2 |
| | io_uring/eventfd.c | rcu_dereference | 1 |
| | io_uring/eventfd.c | rcu_dereference_protected | 2 |
| | io_uring/eventfd.c | eventfd_signal_mask | 2 |
| | io_uring/alloc_cache.h | kfree | 2 |
| | io_uring/eventfd.c | io_eventfd_trigger | 1 |
| | io_uring/eventfd.c | eventfd_ctx_put | 1 |
| | io_uring/advise.c | READ_ONCE | 1 |
| | io_uring/cancel.c | spin_lock | 2 |
| | io_uring/eventfd.c | call_rcu_hurry | 1 |
| | io_uring/eventfd.c | io_eventfd_release | 2 |
| | io_uring/cancel.c | container_of | 2 |
| | io_uring/eventfd.c | rcu_read_unlock | 2 |
| | io_uring/eventfd.c | call_rcu | 1 |
| | io_uring/alloc_cache.c | kmalloc | 1 |
| | io_uring/eventfd.c | atomic_fetch_or | 1 |
| | io_uring/eventfd.c | io_eventfd_put | 3 |
| | io_uring/eventfd.c | eventfd_ctx_fdget | 1 |
| | io_uring/eventfd.c | rcu_assign_pointer | 2 |
| | io_uring/eventfd.c | BIT | 1 |
| | io_uring/cancel.c | copy_from_user | 1 |