LZW is a simple algorithm efficient mainly in text compression. This library provides simple functions for LZW compression and decompression.

```
include "./lzw.inc.php";

$data = "";
$compressed = lzw_compress($data);
var_dump($data === lzw_decompress($compressed));
```