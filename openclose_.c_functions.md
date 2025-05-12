| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| openclose.c | io_uring/eventfd.c | PTR_ERR | 2 |
| | io_uring/epoll.c | u64_to_user_ptr | 2 |
| | io_uring/fs.c | getname | 1 |
| | io_uring/openclose.c | io_close_fixed | 1 |
| | io_uring/cancel.c | spin_unlock | 3 |
| | io_uring/openclose.c | force_o_largefile | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 1 |
| | io_uring/cancel.c | io_ring_submit_unlock | 1 |
| | io_uring/advise.c | io_req_set_res | 3 |
| | io_uring/openclose.c | build_open_flags | 1 |
| | io_uring/openclose.c | io_openat2 | 1 |
| | io_uring/openclose.c | receive_fd | 1 |
| | io_uring/net.c | put_unused_fd | 1 |
| | io_uring/openclose.c | filp_close | 1 |
| | io_uring/io_uring.c | fd_install | 1 |
| | io_uring/fs.c | putname | 2 |
| | io_uring/net.c | rlimit | 1 |
| | io_uring/advise.c | req_set_fail | 3 |
| | io_uring/cancel.c | spin_lock | 1 |
| | io_uring/net.c | io_fixed_fd_install | 1 |
| | io_uring/openclose.c | do_filp_open | 1 |
| | io_uring/cancel.c | unlikely | 2 |
| | io_uring/net.c | __get_unused_fd_flags | 1 |
| | io_uring/openclose.c | io_openat_force_async | 2 |
| | io_uring/cancel.c | io_ring_submit_lock | 1 |
| | io_uring/openclose.c | file_close_fd_locked | 1 |
| | io_uring/eventfd.c | IS_ERR | 2 |
| | io_uring/filetable.c | io_is_uring_fops | 1 |
| | io_uring/openclose.c | copy_struct_from_user | 1 |
| | io_uring/advise.c | io_kiocb_to_cmd | 10 |
| | io_uring/openclose.c | files_lookup_fd_locked | 1 |
| | io_uring/openclose.c | build_open_how | 1 |
| | io_uring/openclose.c | io_fixed_fd_remove | 1 |
| | io_uring/advise.c | READ_ONCE | 10 |
| | io_uring/openclose.c | __io_openat_prep | 2 |
| | io_uring/openclose.c | __io_close_fixed | 1 |