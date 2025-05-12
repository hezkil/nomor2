| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| rsrc.h | io_uring/rsrc.h | io_free_rsrc_node | 1 |
| | io_uring/cancel.c | lockdep_assert_held | 1 |
| | io_uring/io_uring.c | io_req_assign_rsrc_node | 1 |
| | io_uring/rsrc.h | atomic_long_sub | 1 |
| | io_uring/net.c | io_vec_free | 2 |
| | io_uring/io_uring.c | array_index_nospec | 1 |
| | io_uring/rsrc.c | io_put_rsrc_node | 3 |
| | io_uring/io_uring.h | IS_ENABLED | 1 |