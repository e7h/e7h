```c
#include <stdint.h>

typedef struct {
    const char* nickname;
    uint8_t     age;
    const char* specialization[2];
    const char* languages[5];
} profile_t;

static profile_t slay = {
    .nickname = "Slay",
    .age = 17,

    .specialization = {
        "Malware Analyst",
        "Malware Developer"
    },

    .languages = {
        "C/C++",
        "C#",
        "HTML/JavaScript",
        "Python",
        "Golang"
    }
};
```
