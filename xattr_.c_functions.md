| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| xattr.c | io_uring/alloc_cache.c | kmalloc | 2 |
| | io_uring/cancel.c | unlikely | 2 |
| | io_uring/epoll.c | u64_to_user_ptr | 6 |
| | io_uring/xattr.c | setxattr_copy | 1 |
| | io_uring/advise.c | io_kiocb_to_cmd | 9 |
| | io_uring/fs.c | getname | 2 |
| | io_uring/xattr.c | io_xattr_finish | 4 |
| | io_uring/xattr.c | import_xattr_name | 1 |
| | io_uring/xattr.c | file_setxattr | 1 |
| | io_uring/xattr.c | file_getxattr | 1 |
| | io_uring/xattr.c | __io_getxattr_prep | 2 |
| | io_uring/xattr.c | __io_setxattr_prep | 2 |
| | io_uring/advise.c | io_req_set_res | 1 |
| | io_uring/alloc_cache.h | kfree | 3 |
| | io_uring/eventfd.c | PTR_ERR | 2 |
| | io_uring/xattr.c | io_xattr_cleanup | 1 |
| | io_uring/advise.c | WARN_ON_ONCE | 4 |
| | io_uring/xattr.c | filename_setxattr | 1 |
| | io_uring/eventfd.c | IS_ERR | 2 |
| | io_uring/fs.c | putname | 1 |
| | io_uring/advise.c | READ_ONCE | 10 |
| | io_uring/xattr.c | filename_getxattr | 1 |
| | io_uring/alloc_cache.c | kvfree | 1 |