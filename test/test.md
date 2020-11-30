|command|result|
|-------|------|
|./acc_test exec|<font color='green'>PASS</font>|
|uacce load|<font color='green'>PASS</font>|
|hisi_qm load|<font color='green'>PASS</font>|
|hisi_sec2 load|<font color='green'>PASS</font>|
|hisi_zip load|<font color='green'>PASS</font>|
|hisi_hpre load|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-openssl ecdh 0 10 0 generate-sync-param-SECG128-phase1 none none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-openssl ecdh 0 10 0 generate-sync-param-SECG256-phase2 none none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random ecdh 128-16-16-16-16 0 0 generate-sync-param-16~16~16~16~16~16-phase2 none none |<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random ecdh 128-16-16-16-16 6 5 generate-async-param-16~16~16~16~16~16-phase1 none none |<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random cipher 16-16-16 0 0 encrypt-sync-cfb-sm4 none none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random cipher 16-16-16 10 10 encrypt-sync-cfb-sm4 none none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random cipher 16-16-16 10 1 encrypt-async-ofxtb-aes openssl none|UDEF|
|./acc_test hisi-queue-ctx-do-random cipher 16-16-16 10 1 encrypt-sync-cfb-sm4 openssl none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random cipher 16-16-1 3 2 encrypt-async-ofb-aes openssl none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random cipher 16-16-1 0 0 encrypt-sync-ofb-aes loopback none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random aead 16-16-16-16-16 3 2 encrypt-async-ccm-sm4 none none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx-do-random aead 16-16-16-4-1 0 0 decrypt-sync-ccm-sm4 none none|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx aead 16 10|<font color='green'>PASS</font>|
|./acc_test hisi-queue-ctx ecdh 128 10    |<font color='green'>PASS</font>|
|    |<font color='green'>PASS</font>|
|date -R    |<font color='green'>PASS</font>|
