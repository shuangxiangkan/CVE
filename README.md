# CVE
libzip: CVE-2024-55455
https://github.com/nih-at/libzip/issues/475

libzip v1.11.2-3-gd0ebf7fa is vulnerable to Buffer Overflow. A segmentation fault occurs when calling zip_open_from_source with a null error pointer. This results in a crash due to a read access violation.

lunasvg: CVE-2024-55456
https://github.com/sammycage/lunasvg/issues/199

lunasvg v3.0.1 was discovered to contain a segmentation violation via gray_find_cell.