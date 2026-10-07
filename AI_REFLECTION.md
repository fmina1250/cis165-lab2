# AI Reflection

Tools Used: AI tool used was Google Gemini mostly to help identify how to fix problems like installing the compiler and assistance in writing code. 
One decision: One of the prompts I used was that the iostream was read as an error. It then identified that I do not have the compiler downloaded and gave me instructions on how to install the mingw-w64 toolchain. I then accepted the steps in installing it and editting the PATH in order to make it work. The AI was using g++ sum.cpp -o sum to compile but I changed it to g++ -std=c++17 -Wall -Wextra sum.cpp -o sum since that is what the instructions provided.  
Verification: I compiled both code using the provided commands from the instructions. It showed expected results.
```bash
g++ -std=c++17 -Wall -Wextra sum.cpp -o sum
.\sum
g++ -std=c++17 -Wall -Wextra mpg.cpp -o mpg
.\mpg
```
Learning: I learned a bit on how compiler flags work and formatting. I still need to learn more on debugging and software related things.