# Basic freeRTOS example on STM32F030F4

The part is both flash and RAM constrained at
16 kB and 4 kB respectively.
This allows for two pre-emptive (simple) tasks
and a mutext.

Use osMutexWait and osMutexRelease to acquire and
release the mutext.
