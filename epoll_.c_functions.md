| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| epoll.c | io_uring/advise.c | io_kiocb_to_cmd | 4 |
| | io_uring/advise.c | req_set_fail | 2 |
| | io_uring/epoll.c | ep_op_has_event | 1 |
| | io_uring/epoll.c | epoll_sendevents | 1 |
| | io_uring/cancel.c | copy_from_user | 1 |
| | io_uring/epoll.c | u64_to_user_ptr | 2 |
| | io_uring/advise.c | io_req_set_res | 2 |
| | io_uring/advise.c | READ_ONCE | 6 |
| | io_uring/epoll.c | do_epoll_ctl | 1 |