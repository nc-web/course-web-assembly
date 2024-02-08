
# HELLO WASM C

    - 


## Create program c

        <>

        #include <stdio.h>

        int main() {

            printf("Hello WASM \n");
            return 0;

        }


## Compiler a binario

    -

        $ gcc hello-wasm.c -o hello-wasm



## Compiler a binario WASM with Emscripten

    - Install emcripten if you don't have it
    
        $ sudo apt install emscripten

        
    - Compiler
        
        $ emcc hello-wasm.c -o hello-wasm.html