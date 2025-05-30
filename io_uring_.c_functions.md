| Source | Library | Function Utilized | Times Used |
|--------|---------|-------------------|------------|
| io_uring.c | io_uring/io_uring.c | io_get_cqe_overflow | 1 |
| | io_uring/io_uring.c | __wq_list_for_each | 1 |
| | io_uring/io_uring.c | wq_list_add_head | 1 |
| | io_uring/futex.c | io_cache_free | 1 |
| | io_uring/io_uring.c | io_wq_hash_work | 1 |
| | io_uring/io_uring.c | wake_up_all | 1 |
| | io_uring/io_uring.c | list_add_tail | 2 |
| | io_uring/io_uring.c | io_eventfd_flush_signal | 1 |
| | io_uring/io_uring.c | io_uring_add_tctx_node | 1 |
| | io_uring/io_uring.c | io_napi_init | 1 |
| | io_uring/io_uring.c | io_poll_remove_all | 1 |
| | io_uring/io_uring.c | io_prep_linked_timeout | 2 |
| | io_uring/io_uring.c | security_uring_allowed | 1 |
| | io_uring/cancel.c | spin_lock | 12 |
| | io_uring/io_uring.c | ctx_flush_and_put | 3 |
| | io_uring/io_uring.c | io_free_req | 1 |
| | io_uring/io_uring.c | io_uring_clean_tctx | 1 |
| | io_uring/io_uring.c | io_req_track_inflight | 1 |
| | io_uring/io_uring.c | io_run_local_work_continue | 2 |
| | io_uring/alloc_cache.h | io_alloc_cache_init | 5 |
| | io_uring/io_uring.c | wait_for_completion_interruptible_timeout | 1 |
| | io_uring/io_uring.c | io_commit_cqring_flush | 2 |
| | io_uring/io_uring.c | __io_req_set_refcount | 2 |
| | io_uring/io_uring.c | io_req_cache_empty | 2 |
| | io_uring/io_uring.c | io_issue_sqe | 2 |
| | io_uring/io_uring.c | hrtimer_cancel | 1 |
| | io_uring/io_uring.c | smp_store_release | 1 |
| | io_uring/io_uring.c | wake_up_state | 1 |
| | io_uring/io_uring.c | get_current_cred | 1 |
| | io_uring/io_uring.c | trace_io_uring_queue_async_work | 1 |
| | io_uring/io-wq.c | wq_list_empty | 7 |
| | io_uring/io_uring.c | kmem_cache_alloc | 1 |
| | io_uring/io_uring.c | io_queue_sqe_fallback | 3 |
| | io_uring/io_uring.c | BUG_ON | 2 |
| | io_uring/io_uring.c | io_cqring_schedule_timeout | 1 |
| | io_uring/io_uring.c | xa_init_flags | 1 |
| | io_uring/cancel.c | io_file_get_normal | 1 |
| | io_uring/io_uring.c | io_uring_cancel_generic | 1 |
| | io_uring/io_uring.c | io_sqe_buffers_unregister | 1 |
| | io_uring/io_uring.c | list_cut_position | 1 |
| | io_uring/io_uring.c | percpu_counter_sub | 2 |
| | io_uring/io_uring.c | io_cqring_do_overflow_flush | 2 |
| | io_uring/io_uring.c | copy_to_user | 1 |
| | io_uring/io-wq.c | INIT_DELAYED_WORK | 1 |
| | io_uring/io_uring.c | current_cred | 1 |
| | io_uring/io_uring.c | xa_load | 1 |
| | io_uring/eventfd.c | BIT | 5 |
| | io_uring/io_uring.c | __io_cq_unlock_post | 2 |
| | io_uring/io_uring.c | free_uid | 1 |
| | io_uring/cancel.c | spin_unlock | 14 |
| | io_uring/io_uring.c | hrtimer_set_expires | 1 |
| | io_uring/io_uring.c | io_allowed_defer_tw_run | 1 |
| | io_uring/advise.c | READ_ONCE | 31 |
| | io_uring/io_uring.c | io_local_work_pending | 7 |
| | io_uring/io-wq.c | atomic_or | 8 |
| | io_uring/io_uring.c | io_commit_cqring | 2 |
| | io_uring/io_uring.c | init_llist_head | 1 |
| | io_uring/io_uring.c | xa_destroy | 2 |
| | io_uring/io_uring.c | same_thread_group | 1 |
| | io_uring/io_uring.c | put_task_struct_many | 1 |
| | io_uring/io_uring.c | revert_creds | 1 |
| | io_uring/io_uring.c | io_should_wake | 3 |
| | io_uring/io_uring.c | in_compat_syscall | 2 |
| | io_uring/io_uring.c | io_futex_cache_free | 1 |
| | io_uring/io_uring.c | task_sigpending | 3 |
| | io_uring/io_uring.c | llist_reverse_order | 2 |
| | io_uring/alloc_cache.c | kvmalloc_array | 1 |
| | io_uring/io_uring.c | BUILD_BUG_SQE_ELEM | 43 |
| | io_uring/io_uring.c | req_ref_put_and_test | 1 |
| | io_uring/io_uring.c | list_del | 1 |
| | io_uring/io_uring.c | io_req_add_to_cache | 3 |
| | io_uring/io_uring.c | time_after | 2 |
| | io_uring/advise.c | WARN_ON_ONCE | 16 |
| | io_uring/io_uring.c | trace_io_uring_link | 1 |
| | io_uring/io_uring.c | io_sqe_files_unregister | 1 |
| | io_uring/io_uring.c | spin_lock_init | 2 |
| | io_uring/io_uring.c | io_req_defer_failed | 5 |
| | io_uring/io_uring.c | static_branch_unlikely | 1 |
| | io_uring/cancel.c | fget | 2 |
| | io_uring/io_uring.c | get_uid | 1 |
| | io_uring/io_uring.c | trace_io_uring_file_get | 1 |
| | io_uring/cancel.c | io_ring_submit_unlock | 1 |
| | io_uring/io-wq.c | task_work_add | 3 |
| | io_uring/io_uring.c | cleanup | 1 |
| | io_uring/cancel.c | io_ring_submit_lock | 1 |
| | io_uring/io_uring.c | io_account_cq_overflow | 1 |
| | io_uring/io_uring.c | io_run_local_work_locked | 2 |
| | io_uring/fdinfo.c | min | 4 |
| | io_uring/io-wq.c | wq_has_sleeper | 1 |
| | io_uring/io_uring.c | rings_size | 1 |
| | io_uring/io_uring.c | array_size | 3 |
| | io_uring/io_uring.c | io_allocate_scq_urings | 1 |
| | io_uring/io_uring.c | PAGE_ALIGN | 2 |
| | io_uring/io_uring.c | io_extract_req | 1 |
| | io_uring/io_uring.c | synchronize_rcu | 1 |
| | io_uring/io_uring.c | __io_fallback_tw | 3 |
| | io_uring/io_uring.c | io_iopoll_check | 1 |
| | io_uring/io_uring.c | __io_uring_free | 1 |
| | io_uring/io_uring.c | __io_run_local_work_loop | 2 |
| | io_uring/io_uring.c | io_uring_setup | 1 |
| | io_uring/io_uring.c | percpu_ref_get_many | 1 |
| | io_uring/io_uring.c | io_futex_remove_all | 1 |
| | io_uring/io-wq.c | get_task_struct | 1 |
| | io_uring/io_uring.c | io_cqring_event_overflow | 3 |
| | io_uring/io_uring.c | io_arm_poll_handler | 3 |
| | io_uring/epoll.c | u64_to_user_ptr | 3 |
| | io_uring/io_uring.c | percpu_counter_sum | 1 |
| | io_uring/io_uring.c | LIST_HEAD | 1 |
| | io_uring/io_uring.c | restore_saved_sigmask_unless | 1 |
| | io_uring/io_uring.c | array_index_nospec | 4 |
| | io_uring/io_uring.c | io_put_task | 1 |
| | io_uring/io_uring.c | io_run_local_work | 4 |
| | io_uring/io_uring.c | INIT_HLIST_HEAD | 4 |
| | io_uring/io_uring.c | io_uring_fill_params | 1 |
| | io_uring/io_uring.c | io_alloc_hash_table | 1 |
| | io_uring/io_uring.c | io_put_file | 1 |
| | io_uring/io_uring.c | io_kbuf_recycle | 2 |
| | io_uring/cancel.c | copy_from_user | 3 |
| | io_uring/io_uring.c | capable | 1 |
| | io_uring/io_uring.c | mmdrop | 1 |
| | io_uring/io_uring.c | roundup_pow_of_two | 2 |
| | io_uring/io_uring.c | io_for_each_link | 4 |
| | io_uring/io_uring.c | io_cqring_events | 2 |
| | io_uring/futex.c | io_alloc_cache_free | 5 |
| | io_uring/io_uring.c | io_check_restriction | 1 |
| | io_uring/io_uring.c | io_unregister_zcrx_ifqs | 1 |
| | io_uring/io_uring.c | offsetof | 21 |
| | io_uring/io_uring.c | __io_cqring_events | 3 |
| | io_uring/io-wq.c | wake_up_process | 1 |
| | io_uring/cancel.c | io_wq_current_is_worker | 1 |
| | io_uring/io_uring.c | req_ref_put_and_test_atomic | 1 |
| | io_uring/io_uring.c | in_group_p | 1 |
| | io_uring/io_uring.c | llist_empty | 1 |
| | io_uring/io_uring.c | io_submit_flush_completions | 4 |
| | io_uring/cancel.c | lockdep_assert_held | 5 |
| | io_uring/filetable.h | test_bit | 3 |
| | io_uring/eventfd.c | PTR_ERR | 2 |
| | io_uring/io_uring.c | fd_install | 1 |
| | io_uring/io_uring.c | io_create_region | 2 |
| | io_uring/io_uring.c | io_uring_install_fd | 1 |
| | io_uring/io_uring.c | io_req_task_queue | 4 |
| | io_uring/io_uring.c | tctx_inflight | 3 |
| | io_uring/io_uring.c | static_branch_inc | 1 |
| | io_uring/cancel.c | ktime_add_ns | 1 |
| | io_uring/io_uring.c | io_sq_thread_park | 1 |
| | io_uring/io_uring.c | io_kill_timeouts | 1 |
| | io_uring/cancel.c | io_wq_cancel_cb | 3 |
| | io_uring/io_uring.c | wait_for_completion_interruptible | 1 |
| | io_uring/io_uring.c | sizeof_field | 3 |
| | io_uring/io_uring.c | list_rotate_left | 1 |
| | io_uring/io_uring.c | INDIRECT_CALL_2 | 2 |
| | io_uring/io_uring.c | io_get_task_refs | 1 |
| | io_uring/io_uring.c | io_sq_thread_unpark | 1 |
| | io_uring/io_uring.c | io_handle_tw_list | 1 |
| | io_uring/cancel.c | DEFINE_WAIT | 1 |
| | io_uring/io_uring.c | io_clean_op | 1 |
| | io_uring/io_uring.c | io_napi_busy_loop | 1 |
| | io_uring/io_uring.c | io_submit_state_end | 1 |
| | io_uring/io-wq.c | atomic_read | 7 |
| | io_uring/io_uring.c | io_cqring_wait | 1 |
| | io_uring/io-wq.c | io_wq_put_hash | 1 |
| | io_uring/io_uring.c | io_init_req | 1 |
| | io_uring/io_uring.c | io_put_kbuf | 1 |
| | io_uring/io-wq.c | io_wq_is_hashed | 1 |
| | io_uring/io_uring.c | min_t | 1 |
| | io_uring/io_uring.c | clamp | 1 |
| | io_uring/io_uring.c | io_cq_lock | 4 |
| | io_uring/io_uring.c | set_user_sigmask | 1 |
| | io_uring/io_uring.c | fail | 1 |
| | io_uring/io_uring.c | guard | 1 |
| | io_uring/io_uring.c | kmem_cache_alloc_bulk | 1 |
| | io_uring/fdinfo.c | xa_for_each | 3 |
| | io_uring/io_uring.c | io_disarm_next | 1 |
| | io_uring/io_uring.c | INIT_WORK | 1 |
| | io_uring/io_uring.c | issue | 1 |
| | io_uring/io_uring.c | schedule | 3 |
| | io_uring/io_uring.c | ALIGN | 1 |
| | io_uring/io_uring.c | io_sqring_entries | 1 |
| | io_uring/alloc_cache.h | kfree | 10 |
| | io_uring/io_uring.c | current_pending_io | 1 |
| | io_uring/io_uring.c | io_uring_drop_tctx_refs | 3 |
| | io_uring/io_uring.c | mmgrab | 1 |
| | io_uring/io_uring.c | lockdep_assert | 1 |
| | io_uring/io_uring.c | wq_stack_add_head | 1 |
| | io_uring/io_uring.c | io_get_sqe | 1 |
| | io_uring/io_uring.c | io_req_find_next | 2 |
| | io_uring/io_uring.c | io_submit_sqe | 1 |
| | io_uring/io_uring.c | io_sq_thread_finish | 1 |
| | io_uring/io_uring.c | req_need_defer | 3 |
| | io_uring/io_uring.c | prepare_to_wait_exclusive | 1 |
| | io_uring/io_uring.c | io_req_normal_work_add | 1 |
| | io_uring/io_uring.c | S_ISBLK | 1 |
| | io_uring/io_uring.c | override_creds | 1 |
| | io_uring/io_uring.c | user_access_begin | 1 |
| | io_uring/io_uring.c | io_get_time | 1 |
| | io_uring/io_uring.c | io_free_batch_list | 1 |
| | io_uring/io_uring.c | io_match_linked | 2 |
| | io_uring/io_uring.c | gid_valid | 1 |
| | io_uring/io_uring.c | io_cqring_wake | 2 |
| | io_uring/io_uring.c | io_queue_deferred | 1 |
| | io_uring/io_uring.c | set_compat_user_sigmask | 1 |
| | io_uring/io_uring.c | mutex_init | 2 |
| | io_uring/io_uring.c | io_task_work_pending | 1 |
| | io_uring/io_uring.c | hrtimer_set_expires_range_ns | 1 |
| | io_uring/io_uring.c | io_get_ext_arg_reg | 1 |
| | io_uring/io_uring.c | __io_req_find_next_prep | 1 |
| | io_uring/io_uring.c | make_kgid | 1 |
| | io_uring/io_uring.c | io_futex_cache_init | 1 |
| | io_uring/io-wq.c | ERR_PTR | 2 |
| | io_uring/io_uring.c | io_queue_next | 1 |
| | io_uring/io_uring.c | io_file_can_poll | 2 |
| | io_uring/io_uring.c | trace_io_uring_cqring_wait | 1 |
| | io_uring/io_uring.c | list_empty_careful | 1 |
| | io_uring/io_uring.c | io_ring_ctx_wait_and_kill | 2 |
| | io_uring/io-wq.c | set_bit | 2 |
| | io_uring/io_uring.c | io_uring_optable_init | 1 |
| | io_uring/io_uring.c | user_access_end | 2 |
| | io_uring/cancel.c | list_for_each_entry | 2 |
| | io_uring/io_uring.c | io_napi_free | 1 |
| | io_uring/io_uring.c | trace_io_uring_complete | 1 |
| | io_uring/filetable.c | io_is_uring_fops | 2 |
| | io_uring/io-wq.c | __acquires | 1 |
| | io_uring/io_uring.c | __io_cqring_events_user | 2 |
| | io_uring/io_uring.c | security_uring_override_creds | 1 |
| | io_uring/io_uring.c | trace_io_uring_submit_req | 1 |
| | io_uring/io_uring.c | blk_start_plug_nr_ios | 1 |
| | io_uring/io_uring.c | io_uring_create | 1 |
| | io_uring/io_uring.c | io_free_region | 3 |
| | io_uring/io_uring.c | unsafe_get_user | 4 |
| | io_uring/io_uring.c | trace_io_uring_task_work_run | 1 |
| | io_uring/io_uring.c | io_flush_timeouts | 1 |
| | io_uring/io_uring.c | __io_prep_linked_timeout | 2 |
| | io_uring/io_uring.c | raw_spin_unlock_irq | 2 |
| | io_uring/io_uring.c | struct_size | 1 |
| | io_uring/io_uring.c | atomic_andnot | 3 |
| | io_uring/io_uring.c | io_init_fail_req | 9 |
| | io_uring/cancel.c | ARRAY_SIZE | 2 |
| | io_uring/io_uring.c | io_uring_try_cancel_uring_cmd | 1 |
| | io_uring/io_uring.c | anon_inode_create_getfile | 1 |
| | io_uring/io_uring.c | req_ref_put | 1 |
| | io_uring/eventfd.c | atomic_set | 6 |
| | io_uring/io_uring.c | percpu_ref_put | 6 |
| | io_uring/io_uring.c | io_destroy_buffers | 1 |
| | io_uring/io_uring.c | get_cred | 1 |
| | io_uring/io_uring.c | io_eventfd_unregister | 1 |
| | io_uring/io-wq.c | list_empty | 9 |
| | io_uring/alloc_cache.c | kmalloc | 2 |
| | io_uring/io_uring.c | raw_spin_lock_irq | 2 |
| | io_uring/io-wq.c | atomic_dec | 2 |
| | io_uring/io_uring.c | alloc_workqueue | 1 |
| | io_uring/io_uring.c | io_req_put_rsrc_nodes | 1 |
| | io_uring/io_uring.c | S_ISREG | 1 |
| | io_uring/io_uring.c | percpu_ref_exit | 2 |
| | io_uring/io-wq.c | atomic_inc | 2 |
| | io_uring/io_uring.c | io_eventfd_signal | 1 |
| | io_uring/io_uring.c | autoremove_wake_function | 1 |
| | io_uring/io_uring.c | io_uring_try_cancel_iowq | 1 |
| | io_uring/io_uring.c | __io_run_local_work | 2 |
| | io_uring/io_uring.c | io_wq_exit_start | 1 |
| | io_uring/io_uring.c | static_branch_dec | 1 |
| | io_uring/io_uring.c | io_uring_get_file | 1 |
| | io_uring/io_uring.c | percpu_ref_get | 4 |
| | io_uring/io_uring.c | hrtimer_update_function | 1 |
| | io_uring/io_uring.c | io_rsrc_cache_init | 1 |
| | io_uring/io_uring.c | current_user | 1 |
| | io_uring/io-wq.c | io_wq_enqueue | 1 |
| | io_uring/io_uring.c | ns_capable_noaudit | 1 |
| | io_uring/io_uring.c | io_move_task_work_from_local | 1 |
| | io_uring/io_uring.c | trace_io_uring_local_work_run | 1 |
| | io_uring/io_uring.c | io_cancel_defer_files | 1 |
| | io_uring/io_uring.c | io_get_sequence | 1 |
| | io_uring/io_uring.c | io_queue_sqe | 2 |
| | io_uring/io_uring.c | __BUILD_BUG_VERIFY_OFFSET_SIZE | 2 |
| | io_uring/io_uring.c | io_req_complete_post | 1 |
| | io_uring/io_uring.c | io_drain_req | 1 |
| | io_uring/io-wq.c | func | 1 |
| | io_uring/io_uring.c | io_sq_offload_create | 1 |
| | io_uring/io_uring.c | io_waitid_remove_all | 1 |
| | io_uring/io_uring.c | ilog2 | 1 |
| | io_uring/io_uring.c | io_req_set_refcount | 1 |
| | io_uring/io-wq.c | wake_up | 3 |
| | io_uring/io_uring.c | llist_del_all | 6 |
| | io_uring/futex.c | __set_current_state | 3 |
| | io_uring/io-wq.c | schedule_delayed_work | 1 |
| | io_uring/io_uring.c | io_req_caches_free | 2 |
| | io_uring/advise.c | io_req_set_res | 3 |
| | io_uring/io-wq.c | set_current_state | 1 |
| | io_uring/futex.c | io_tw_lock | 3 |
| | io_uring/cancel.c | io_rsrc_node_lookup | 1 |
| | io_uring/io_uring.c | put_cred | 3 |
| | io_uring/io_uring.c | hrtimer_setup_on_stack | 2 |
| | io_uring/io_uring.c | BUILD_BUG_SQE_ELEM_SIZE | 1 |
| | io_uring/io_uring.c | get_timespec64 | 1 |
| | io_uring/io_uring.c | io_fill_cqe_aux | 3 |
| | io_uring/io_uring.c | io_uring_sanitise_params | 1 |
| | io_uring/io_uring.c | io_validate_ext_arg | 1 |
| | io_uring/io-wq.c | init_task_work | 2 |
| | io_uring/io_uring.c | xa_init | 1 |
| | io_uring/io_uring.c | io_sqring_full | 1 |
| | io_uring/io_uring.c | io_submit_sqes | 1 |
| | io_uring/io_uring.c | io_sqpoll_wait_sq | 1 |
| | io_uring/io_uring.c | io_submit_state_start | 1 |
| | io_uring/cancel.c | io_match_task_safe | 2 |
| | io_uring/io_uring.c | flush_delayed_work | 4 |
| | io_uring/io_uring.c | need_resched | 4 |
| | io_uring/io_uring.c | io_ring_ctx_alloc | 1 |
| | io_uring/io_uring.c | io_arm_ltimeout | 2 |
| | io_uring/io-wq.c | put_task_struct | 2 |
| | io_uring/io_uring.c | __io_req_task_work_add | 1 |
| | io_uring/io_uring.c | io_preinit_req | 1 |
| | io_uring/io_uring.c | register_sysctl_init | 1 |
| | io_uring/io_uring.c | io_poll_wq_wake | 1 |
| | io_uring/cancel.c | finish_wait | 2 |
| | io_uring/io-wq.c | __releases | 1 |
| | io_uring/io_uring.c | audit_uring_exit | 1 |
| | io_uring/io_uring.c | percpu_counter_add | 1 |
| | io_uring/io-wq.c | io_run_task_work | 6 |
| | io_uring/io_uring.c | trace_io_uring_create | 1 |
| | io_uring/io_uring.c | io_req_local_work_add | 1 |
| | io_uring/io_uring.c | io_get_ext_arg | 1 |
| | io_uring/io_uring.c | ktime_add | 1 |
| | io_uring/io_uring.c | io_req_task_queue_fail | 4 |
| | io_uring/io_uring.c | io_allowed_run_tw | 2 |
| | io_uring/io_uring.c | trace_io_uring_defer | 1 |
| | io_uring/io_uring.c | list_for_each_entry_reverse | 1 |
| | io_uring/io_uring.c | io_req_assign_rsrc_node | 1 |
| | io_uring/io_uring.c | __io_issue_sqe | 2 |
| | io_uring/io_uring.c | ktime_compare | 1 |
| | io_uring/io_uring.c | io_prep_async_work | 2 |
| | io_uring/io_uring.c | smp_rmb | 1 |
| | io_uring/cancel.c | unlikely | 56 |
| | io_uring/cancel.c | __must_hold | 11 |
| | io_uring/filetable.h | io_file_get_flags | 1 |
| | io_uring/io-wq.c | list_del_init | 2 |
| | io_uring/io_uring.c | io_uring_del_tctx_node | 1 |
| | io_uring/io-wq.c | complete | 2 |
| | io_uring/io_uring.c | llist_add | 2 |
| | io_uring/io_uring.c | percpu_ref_put_many | 1 |
| | io_uring/io_uring.c | kmem_cache_free | 1 |
| | io_uring/cancel.c | mutex_unlock | 22 |
| | io_uring/cancel.c | timespec64_to_ktime | 1 |
| | io_uring/io_uring.c | __io_uring_add_tctx_node | 1 |
| | io_uring/io_uring.c | io_queue_linked_timeout | 3 |
| | io_uring/io-wq.c | INIT_LIST_HEAD | 7 |
| | io_uring/io_uring.c | percpu_ref_kill | 1 |
| | io_uring/io_uring.c | file_inode | 3 |
| | io_uring/io-wq.c | kzalloc | 1 |
| | io_uring/io_uring.c | check_shl_overflow | 1 |
| | io_uring/io_uring.c | io_kbuf_drop_legacy | 1 |
| | io_uring/io_uring.c | max | 2 |
| | io_uring/io-wq.c | raw_spin_lock_init | 1 |
| | io_uring/io_uring.c | io_cqring_timer_wakeup | 1 |
| | io_uring/io_uring.c | trace_io_uring_req_failed | 1 |
| | io_uring/io_uring.c | io_unregister_personality | 1 |
| | io_uring/io_uring.c | destroy_hrtimer_on_stack | 1 |
| | io_uring/io_uring.c | io_req_cqe_overflow | 2 |
| | io_uring/fdinfo.c | task_work_pending | 2 |
| | io_uring/io_uring.c | io_iopoll_try_reap_events | 1 |
| | io_uring/eventfd.c | IS_ERR | 2 |
| | io_uring/io_uring.c | io_uring_try_cancel_requests | 3 |
| | io_uring/io-wq.c | cond_resched | 8 |
| | io_uring/cancel.c | fput | 2 |
| | io_uring/io_uring.c | init_waitqueue_func_entry | 1 |
| | io_uring/io_uring.c | tctx_task_work_run | 1 |
| | io_uring/io_uring.c | __io_cq_lock | 2 |
| | io_uring/io_uring.c | __io_cqring_wait_schedule | 1 |
| | io_uring/io_uring.c | io_queue_iowq | 5 |
| | io_uring/io_uring.c | io_commit_sqring | 1 |
| | io_uring/cancel.c | container_of | 20 |
| | io_uring/io_uring.c | io_fill_cqe_req | 2 |
| | io_uring/filetable.c | check_add_overflow | 2 |
| | io_uring/io_uring.c | poll_wait | 1 |
| | io_uring/io_uring.c | queue_work | 1 |
| | io_uring/io_uring.c | io_cqring_wait_schedule | 1 |
| | io_uring/io_uring.c | io_ring_ctx_free | 1 |
| | io_uring/io_uring.c | hrtimer_start_expires | 1 |
| | io_uring/io_uring.c | io_req_complete_defer | 3 |
| | io_uring/io_uring.c | list_first_entry | 4 |
| | io_uring/io_uring.c | memcpy | 1 |
| | io_uring/io-wq.c | init_completion | 2 |
| | io_uring/alloc_cache.c | kvfree | 2 |
| | io_uring/io_uring.c | req_ref_get | 1 |
| | io_uring/io_uring.c | init_waitqueue_head | 3 |
| | io_uring/io-wq.c | INIT_WQ_LIST | 3 |
| | io_uring/io_uring.c | refcount_add | 1 |
| | io_uring/io_uring.c | io_region_get_ptr | 2 |
| | io_uring/cancel.c | io_slot_file | 1 |
| | io_uring/io_uring.c | io_alloc_req | 1 |
| | io_uring/io_uring.c | io_get_cqe | 1 |
| | io_uring/io_uring.c | io_rings_free | 3 |
| | io_uring/io-wq.c | wq_list_add_tail | 1 |
| | io_uring/io_uring.c | io_activate_pollwq | 1 |
| | io_uring/io_uring.c | prep | 1 |
| | io_uring/io_uring.c | io_queue_async | 1 |
| | io_uring/io_uring.c | io_uring_allowed | 1 |
| | io_uring/io_uring.c | io_assign_file | 2 |
| | io_uring/io_uring.c | try_cmpxchg | 1 |
| | io_uring/io_uring.c | io_iopoll_req_issued | 1 |
| | io_uring/io_uring.c | io_free_alloc_caches | 2 |
| | io_uring/io_uring.c | io_has_work | 3 |
| | io_uring/io_uring.c | io_ring_add_registered_file | 1 |
| | io_uring/io-wq.c | likely | 6 |
| | io_uring/cancel.c | io_file_get_fixed | 1 |
| | io_uring/io_uring.c | io_slot_flags | 1 |
| | io_uring/io_uring.c | io_do_iopoll | 2 |
| | io_uring/io_uring.c | __io_cqring_overflow_flush | 3 |
| | io_uring/io_uring.c | get_unused_fd_flags | 1 |
| | io_uring/io_uring.c | io_wq_worker_stopped | 1 |
| | io_uring/io_uring.c | percpu_counter_read_positive | 1 |
| | io_uring/io-wq.c | clear_bit | 2 |
| | io_uring/io_uring.c | io_shutdown_zcrx_ifqs | 1 |
| | io_uring/io_uring.c | WRITE_ONCE | 9 |
| | io_uring/io_uring.c | blk_finish_plug | 1 |
| | io_uring/io_uring.c | io_init_drain | 1 |
| | io_uring/io_uring.c | req_fail_link_node | 2 |
| | io_uring/advise.c | req_set_fail | 2 |
| | io_uring/io_uring.c | audit_uring_entry | 1 |
| | io_uring/cancel.c | mutex_lock | 21 |
| | io_uring/io-wq.c | BUILD_BUG_ON | 16 |
| | io_uring/io_uring.c | io_prep_async_link | 2 |
| | io_uring/io_uring.c | io_rsrc_cache_free | 1 |
| | io_uring/cancel.c | prepare_to_wait | 1 |
| | io_uring/io_uring.c | trace_io_uring_cqe_overflow | 1 |
| | io_uring/io_uring.c | llist_for_each_entry_safe | 1 |
| | io_uring/io_uring.c | kmem_cache_create | 1 |
| | io_uring/io_uring.c | io_submit_fail_init | 1 |
| | io_uring/io_uring.c | percpu_ref_init | 1 |
| | io_uring/io_uring.c | io_should_terminate_tw | 1 |
| | io_uring/io_uring.c | io_fallback_tw | 2 |
| | io_uring/io_uring.c | io_cq_unlock_post | 4 |
| | io_uring/futex.c | io_req_task_work_add | 5 |
| | io_uring/io_uring.c | io_uring_unreg_ringfd | 1 |
| | io_uring/io_uring.c | io_cqring_overflow_kill | 2 |
| | io_uring/io-wq.c | __set_notify_signal | 1 |
| | io_uring/io_uring.c | __io_arm_ltimeout | 1 |
| | io_uring/alloc_cache.c | memset | 6 |
| | io_uring/io_uring.c | smp_mb | 2 |