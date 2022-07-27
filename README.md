# gnl_04-
get next line with only 1 byte reachable by valgirnd

==58252== 
==58252== HEAP SUMMARY:
==58252==     in use at exit: 1 bytes in 1 blocks
==58252==   total heap usage: 514 allocs, 513 frees, 162,302 bytes allocated
==58252== 
==58252== 1 bytes in 1 blocks are still reachable in loss record 1 of 1
==58252==    at 0x483B7F3: malloc (in /usr/lib/x86_64-linux-gnu/valgrind/vgpreload_memcheck-amd64-linux.so)
==58252==    by 0x109799: ft_strdup (in /home/ds/42/gnl-tests_04/a.out)
==58252==    by 0x109612: ft_formbox (in /home/ds/42/gnl-tests_04/a.out)
==58252==    by 0x10926B: get_next_line (in /home/ds/42/gnl-tests_04/a.out)
==58252==    by 0x109AF4: main (in /home/ds/42/gnl-tests_04/a.out)
==58252== 
==58252== LEAK SUMMARY:
==58252==    definitely lost: 0 bytes in 0 blocks
==58252==    indirectly lost: 0 bytes in 0 blocks
==58252==      possibly lost: 0 bytes in 0 blocks
==58252==    still reachable: 1 bytes in 1 blocks
==58252==         suppressed: 0 bytes in 0 blocks
==58252== 
==58252== For lists of detected and suppressed errors, rerun with: -s
==58252== ERROR SUMMARY: 0 errors from 0 contexts (suppressed: 0 from 0)
