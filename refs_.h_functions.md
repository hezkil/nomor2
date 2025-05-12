| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| refs.h | io_uring/io_uring.c | __io_req_set_refcount | 1 |
| | io_uring/refs.h | atomic_inc_not_zero | 1 |
| | io_uring/refs.h | data_race | 1 |
| | io_uring/eventfd.c | atomic_set | 1 |
| | io_uring/refs.h | req_ref_zero_or_close_to_overflow | 4 |
| | io_uring/io-wq.c | atomic_dec | 1 |
| | io_uring/io-wq.c | atomic_read | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 8 |
| | io_uring/io-wq.c | likely | 1 |
| | io_uring/io-wq.c | atomic_inc | 1 |
| | io_uring/io-wq.c | atomic_dec_and_test | 2 |