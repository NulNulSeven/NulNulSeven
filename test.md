graph TD
    A[Extended Computer-Brain Analogical Core]

    subgraph Computer System Architecture
        C1[Motherboard Core]
        C2[CPU: Processing Unit]
        C3[Northbridge Controller]
        C4[Southbridge Controller]
        C5[BIOS Firmware]
        C6[Bus & I/O Interface]
    end

    subgraph Biological Neural Framework
        B1[Central Nervous System]
        B2[Thalamus Complex]
        B3[Hypothalamus Node]
        B4[Epithalamus Gate]
        B5[Cerebral Cortex]
        B6[Peripheral Nervous System]
    end

    subgraph Analogical Mapping Layer
        M1[CPU ↔ Thalamus]
        M2[Northbridge ↔ Hypothalamus]
        M3[Southbridge ↔ Epithalamus]
        M4[Memory ↔ Cortex]
        M5[Bus ↔ Peripheral NS]
    end

    subgraph Inputs
        I1[User Input Signal]
        I2[Sensory Environment Data]
        I3[System Boot Power Trigger]
    end

    subgraph Outputs
        O1[Processed Thought Pattern]
        O2[Motor Output Command]
        O3[Externalized Behavior Path]
    end

    %% Core connections
    A --> C1
    A --> B1
    A --> M1
    A --> I1
    A --> O1

    %% Computer Architecture
    C1 --> C2
    C1 --> C3
    C1 --> C4
    C1 --> C5
    C1 --> C6

    %% Neural Framework
    B1 --> B2
    B1 --> B3
    B1 --> B4
    B1 --> B5
    B1 --> B6

    %% Inputs
    I1 --> C2
    I2 --> B2
    I3 --> C5

    %% Analogical Mapping
    C2 --> M1 --> B2
    C3 --> M2 --> B3
    C4 --> M3 --> B4
    C5 --> M4 --> B5
    C6 --> M5 --> B6

    %% Outputs
    B5 --> O1
    B6 --> O2
    B4 --> O3

    %% Feedback loop
    O1 --> A
    O2 --> A
    O3 --> A
