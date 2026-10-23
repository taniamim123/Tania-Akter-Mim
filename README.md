```c
#include <stdio.h>

typedef struct {
    char* name;
    char* primary_langs[4];
    char* core_domains[4];
    char* status;
} Developer;

int main() {
    Developer dev = {
        .name = "Tania Akter Mim",
        .primary_langs = {"C", "C++", "Python", "C#"},
        .core_domains = {"Data Science", "Cryptography", "Networking", "Databases"},
        .status = "Decoding complex algorithms & engineering secure systems 🔐"
    };
    printf("Status: %s\n", dev.status);
    return 0;
}
