| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| sync.c | io_uring/cancel.c | unlikely | 3 |
| | io_uring/advise.c | io_req_set_res | 3 |
| | io_uring/sync.c | vfs_fallocate | 1 |
| | io_uring/sync.c | vfs_fsync_range | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 3 |
| | io_uring/sync.c | sync_file_range | 1 |
| | io_uring/advise.c | READ_ONCE | 9 |
| | io_uring/rw.c | fsnotify_modify | 1 |
| | io_uring/advise.c | io_kiocb_to_cmd | 6 |