# EmbedKit_Sapana-Bhavsar
# EmbedKit - Embedded C Utility Library

**Developer Name:** Sapana Santosh Bhavsar
**Position:** Embedded Developer Assignment (Fresher)

## Modules Overview
* **ringbuf.c**: A standalone circular/ring buffer implementation for `uint8_t` data with optimized bitwise index wrapping for microcontrollers.

## How to Build and Run

### Method 1: Locally on Laptop (Using GCC Compiler)
To compile and run the ring buffer program using gcc, execute the following commands in your terminal:
```bash
gcc -Wall -std=c99 ringbuf.c -o ringbuf
./ringbuf
```

### Method 2: Online Verification (Using Rextester GCC Compiler)
This code is also fully tested and verified online. You can run it directly:
1. Go to the online compiler: [Rextester GCC Compiler](https://rextester.com/l/c_online_compiler_gcc)
2. Copy and paste the full contents of `ringbuf.c` into the editor.
3. In the compiler options, ensure `-Wall -std=c99` is provided.
4. Click **Run it (F5)** to see the verified automated output sequence.
