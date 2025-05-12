| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| notif.h | io_uring/cancel.c | __must_hold | 1 |
| | io_uring/net.c | io_notif_to_data | 2 |
| | io_uring/advise.c | io_kiocb_to_cmd | 1 |
| | io_uring/notif.c | io_tx_ubuf_complete | 1 |
| | io_uring/memmap.c | __io_account_mem | 1 |