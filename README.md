CHASH
====

Cleverhash "CHASH" the X13 PoW/PoS Cryptocurrency.

Algorithm: X13 POW/POS

Ticker: CHASH

Current Version "3.0.0.0"

Max Coins: 2,000,000 CHASH

RPC Port: 28194

30 Blocks to mature

Block Reward Schedule:

Block 1 is 2,000,000  CHASH

Block 2-500,000 are 0 CHASH

X13 -(blake, bmw, groestl, jh, keccak, skein, luffa, cubehash, shavite, simd, echo, hamsi, fugue)

More info can be found at:

Website - http://cleverhash.com

Bitcointalk - https://bitcointalk.org/index.php?topic=826541.0

Whitepaper - https://drive.google.com/file/d/0Bz5jVqQaTSBcTFl2akd0QTJlN1k/view?usp=sharing


==========================================================

Daemon Build Instructions:

git clone https://github.com/Cleverhash/CHASH.git

cd CHASH/src

mkdir obj

chmod +x leveldb/build_detect_platform

make -f makefile.unix
