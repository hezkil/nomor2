| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| notif.c | io_uring/net.c | io_notif_to_data | 2 |
| | io_uring/memmap.c | __io_unaccount_mem | 1 |
| | io_uring/eventfd.c | refcount_dec_and_test | 1 |
| | io_uring/notif.c | io_tx_ubuf_complete | 1 |
| | io_uring/io_uring.c | lockdep_assert | 1 |
| | io_uring/cancel.c | container_of | 3 |
| | io_uring/cancel.c | unlikely | 6 |
| | io_uring/io_uring.c | __io_req_task_work_add | 1 |
| | io_uring/cancel.c | __must_hold | 1 |
| | io_uring/notif.c | net_zcopy_get | 2 |
| | io_uring/notif.c | skb_zcopy_init | 1 |
| | io_uring/msg_ring.c | cmd_to_io_kiocb | 4 |
| | io_uring/io_uring.c | io_alloc_req | 1 |
| | io_uring/notif.c | refcount_read | 1 |
| | io_uring/eventfd.c | refcount_set | 1 |
| | io_uring/io_uring.c | WRITE_ONCE | 2 |
| | io_uring/io_uring.c | io_get_task_refs | 1 |
| | io_uring/notif.c | skb_zcopy | 1 |
| | io_uring/futex.c | io_req_task_complete | 1 |