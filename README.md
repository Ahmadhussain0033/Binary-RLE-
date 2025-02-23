#RLE File Compressor (In-Place, No Reading, No New Files)
This project implements a Run-Length Encoding (RLE) algorithm that compresses a file containing millions of 0s and 1s, while following strict constraints:

##🚫 No direct reading of data – The algorithm cannot read the file but can manipulate it.
##✍️ Limited operations – It can only write and remove 0s and 1s from the file.
##📏 File length n – The input file consists of n characters, with a random distribution of 0s and 1s.
##📉 Compression goal – The algorithm must shorten the file while ensuring the original file can be reconstructed from the compressed version.
##🔢 No hex, no spaces – The encoding must only use 0s and 1s, without hexadecimal, spaces, or special characters.
##❌ No new files – The compression must happen in-place, meaning no extra files can be created.
