# libarchive-harness-win - CVE-2024-20696

Blog post: https://clearbluejar.github.io/posts/patch-tuesday-diffing-cve-2024-20696-windows-libarchive-rce/

A simple test harness for CVE-2024-20696

1. Download a version of archiveint.dll that you want to test
2. Update the path [here](libarchive-harness-win.cpp#94)
3. Update the file path to point to the test archive to process. A sample one [bsdtar-invalid-read.rar](bsdtar-invalid-read.rar)
