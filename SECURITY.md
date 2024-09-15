### How to Change Log level
(_Just called this file "SECURITY.md so that it appears on landing page of repository_)

>[!Note]
>Follow the directions below to get a full history of all changes made to AutoCorrect2.ahk file (saved to the same folder).


```diff
--- FileCopy "AutoCorrect.ahk", "AutoCorrect_backup.ahk", 1
+++ backupFilename := "AutoCorrect_" A_YYYY "-" A_MM "-" A_DD "_" A_Hour "-" A_Min "-" A_Sec ".ahk"
+++ ; logfile saved as 'AutoCorrect_YYYY-MM-DD_HH24-MI-SS.ahk'
+++ FileCopy "AutoCorrect.ahk", backupFilename, 1

