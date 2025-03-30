# Extended Computer-Brain Analogical Framework

## Flowchart Diagram

```mermaid
flowchart TD
    %% Main systems
    COMP[Computer System] --> MB[Motherboard]
    BRAIN[Brain System] --> CNS[Central Nervous System]
    
    %% Computer subsystems
    MB --> CPU[Central Processing Unit]
    MB --> NB[Northbridge]
    MB --> SB[Southbridge]
    MB --> IO[Super I/O]
    MB --> BIOS[BIOS/Firmware]
    MB --> MEM[Memory Systems]
    MB --> BUS[Bus Systems]
    
    %% Brain subsystems
    CNS --> DIEN[Diencephalon]
    CNS --> CORT[Cerebral Cortex]
    CNS --> CBELL[Cerebellum]
    CNS --> BS[Brainstem]
    CNS --> PNS[Peripheral Neural Connections]
    
    %% Diencephalon breakdown
    DIEN --> THAL[Thalamus]
    DIEN --> HYPO[Hypothalamus]
    DIEN --> EPIT[Epithalamus]
    DIEN --> SUBT[Subthalamus]
    
    %% CPU relationships
    CPU --> PROC[Processing Units]
    CPU --> CACHE[Cache Memory]
    CPU --> INSTRUCT[Instruction Sets]
    
    %% Thalamus relationships
    THAL --> RELAY[Sensory Relay]
    THAL --> INTEG[Information Integration]
    THAL --> FILT[Sensory Filtering]
    
    %% Bridge systems
    NB --> MEMCON[Memory Controller]
    NB --> GPUINT[GPU Interface]
    SB --> STORAGE[Storage Controller]
    SB --> PERIPH[Peripheral Controller]
    
    %% Equivalent systems
    THAL -.-> |"Analogous to"| CPU
    HYPO -.-> |"Analogous to"| NB
    EPIT -.-> |"Analogous to"| SB
    CORT -.-> |"Analogous to"| MEM
    BS -.-> |"Analogous to"| IO
    PNS -.-> |"Analogous to"| BUS
