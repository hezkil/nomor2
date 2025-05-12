| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| splice.c | io_uring/cancel.c | io_ring_submit_unlock | 1 |
| | io_uring/cancel.c | io_file_get_normal | 1 |
| | io_uring/cancel.c | fput | 2 |
| | io_uring/advise.c | READ_ONCE | 6 |
| | io_uring/cancel.c | io_slot_file | 1 |
| | io_uring/cancel.c | io_ring_submit_lock | 1 |
| | io_uring/advise.c | req_set_fail | 2 |
| | io_uring/rsrc.c | io_put_rsrc_node | 1 |
| | io_uring/splice.c | __io_splice_prep | 2 |
| | io_uring/splice.c | io_splice_get_file | 2 |
| | io_uring/cancel.c | unlikely | 1 |
| | io_uring/advise.c | io_req_set_res | 2 |
| | io_uring/advise.c | io_kiocb_to_cmd | 6 |
| | io_uring/splice.c | do_tee | 1 |
| | io_uring/cancel.c | io_rsrc_node_lookup | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 2 |
| | io_uring/splice.c | do_splice | 1 |