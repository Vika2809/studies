14. Hash atskiras, jo tie ir dazadi komiti, bet ja terminali palaiz git diff komandu ta paradija viniegu atskiribu starp README.md failiem module_1 un module_2 mape, git atpazistinaja ka bilde ir tas pats fails.
-viktorija@Viktorijas-MBP studies % git diff --no-index module_1 module_2
-diff --git a/module_1/.DS_Store b/module_1/.DS_Store
-deleted file mode 100644
-index 5008ddf..0000000
-Binary files a/module_1/.DS_Store and /dev/null differ
-diff --git a/module_1/README.md b/module_2/README.md
-index 753c63d..e69de29 100644
---- a/module_1/README.md
-+++ b/module_2/README.md
-@@ -1,3 +0,0 @@
-# DevOps Repozitorijs
-
-## _Viktorija Matjuka_

16. izmainas parabauditas var veikt ar git log vai nu apskatit vinas github desktop
17. Ja Laura veikusi komitus pagajusa gada septembri , atrasti ar sis komandas palidzinu git log --since "SEP 1 2021" --until "SEP 30 2021" --author="Laura Pacilio"
18. Ja vienu kommitu 29 Aprili si gada, 
-commit 78f90a64b5d4f615efdcbdb92d88291012aba7c4
-Merge: f19848bab 2928967b4
-Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
-Date:   Fri Apr 29 11:58:17 2022 -0400

    -Merge pull request #30956 from tigerblue77/patch-1
    
    -Update apt.mdx
*Iespejams ka veiktas izmainas 16 aprili tika komitotatas no laika posma 20-21 aprilim. 