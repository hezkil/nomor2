| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| uring_cmd.c | io_uring/net.c | io_alloc_cache_vec_kasan | 1 |
| | io_uring/net.c | io_is_compat | 1 |
| | io_uring/io_uring.c | memcpy | 1 |
| | io_uring/uring_cmd.c | io_uring_cmd_setsockopt | 1 |
| | io_uring/uring_cmd.c | USER_SOCKPTR | 2 |
| | io_uring/advise.c | io_req_set_res | 2 |
| | io_uring/uring_cmd.c | task_work_cb | 1 |
| | io_uring/cancel.c | hlist_for_each_entry_safe | 1 |
| | io_uring/uring_cmd.c | KERNEL_SOCKPTR | 1 |
| | io_uring/net.c | io_prep_reg_iovec | 1 |
| | io_uring/io_uring.c | __io_req_task_work_add | 1 |
| | io_uring/io_uring.c | smp_store_release | 1 |
| | io_uring/io-wq.c | BUILD_BUG_ON | 1 |
| | io_uring/uring_cmd.c | security_uring_cmd | 1 |
| | io_uring/cancel.c | lockdep_assert_held | 1 |
| | io_uring/msg_ring.c | cmd_to_io_kiocb | 7 |
| | io_uring/io_uring.c | io_submit_flush_completions | 1 |
| | io_uring/io_uring.c | offsetof | 1 |
| | io_uring/uring_cmd.c | io_uring_cmd_getsockopt | 1 |
| | io_uring/alloc_cache.h | io_alloc_cache_put | 1 |
| | io_uring/net.c | io_vec_free | 2 |
| | io_uring/net.c | io_import_reg_buf | 1 |
| | io_uring/uring_cmd.c | ioctl | 2 |
| | io_uring/io_uring.c | io_should_terminate_tw | 1 |
| | io_uring/futex.c | hlist_add_head | 1 |
| | io_uring/advise.c | req_set_fail | 2 |
| | io_uring/futex.c | io_req_task_work_add | 1 |
| | io_uring/alloc_cache.h | kfree | 2 |
| | io_uring/uring_cmd.c | uring_cmd | 2 |
| | io_uring/uring_cmd.c | io_uring_cmd_prep_setup | 1 |
| | io_uring/uring_cmd.c | do_sock_getsockopt | 1 |
| | io_uring/advise.c | io_kiocb_to_cmd | 6 |
| | io_uring/epoll.c | u64_to_user_ptr | 2 |
| | io_uring/uring_cmd.c | io_req_queue_iowq | 1 |
| | io_uring/uring_cmd.c | do_sock_setsockopt | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 1 |
| | io_uring/net.c | io_uring_alloc_async_data | 1 |
| | io_uring/advise.c | READ_ONCE | 12 |
| | io_uring/uring_cmd.c | uring_sqe_size | 1 |
| | io_uring/uring_cmd.c | hlist_del | 1 |
| | io_uring/net.c | io_import_reg_vec | 1 |
| | io_uring/cancel.c | io_ring_submit_lock | 2 |
| | io_uring/io_uring.c | io_req_complete_defer | 1 |
| | io_uring/uring_cmd.c | io_req_set_cqe32_extra | 1 |
| | io_uring/uring_cmd.c | io_req_uring_cleanup | 3 |
| | io_uring/cancel.c | io_ring_submit_unlock | 2 |
| | io_uring/uring_cmd.c | io_uring_cmd_del_cancelable | 1 |