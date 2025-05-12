| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| fs.c | io_uring/advise.c | WARN_ON_ONCE | 5 |
| | io_uring/cancel.c | unlikely | 5 |
| | io_uring/fs.c | getname | 7 |
| | io_uring/fs.c | do_rmdir | 1 |
| | io_uring/advise.c | io_req_set_res | 5 |
| | io_uring/eventfd.c | IS_ERR | 8 |
| | io_uring/advise.c | READ_ONCE | 19 |
| | io_uring/fs.c | do_symlinkat | 1 |
| | io_uring/fs.c | putname | 9 |
| | io_uring/fs.c | do_renameat2 | 1 |
| | io_uring/advise.c | io_kiocb_to_cmd | 14 |
| | io_uring/fs.c | do_linkat | 1 |
| | io_uring/eventfd.c | PTR_ERR | 8 |
| | io_uring/epoll.c | u64_to_user_ptr | 8 |
| | io_uring/fs.c | getname_uflags | 1 |
| | io_uring/fs.c | do_mkdirat | 1 |
| | io_uring/fs.c | do_unlinkat | 1 |