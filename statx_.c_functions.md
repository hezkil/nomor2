| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| statx.c | io_uring/fs.c | getname_uflags | 1 |
| | io_uring/eventfd.c | IS_ERR | 1 |
| | io_uring/statx.c | do_statx | 1 |
| | io_uring/fs.c | putname | 1 |
| | io_uring/eventfd.c | PTR_ERR | 1 |
| | io_uring/advise.c | io_kiocb_to_cmd | 3 |
| | io_uring/epoll.c | u64_to_user_ptr | 2 |
| | io_uring/advise.c | io_req_set_res | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 1 |
| | io_uring/advise.c | READ_ONCE | 5 |