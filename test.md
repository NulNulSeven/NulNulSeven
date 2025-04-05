graph TD
    CORE[Extended Computer-Brain Analogical Core]

    subgraph Computer System Architecture
        C1[Motherboard Core]
        C2[Central Processing Unit (CPU)]
        C3[Northbridge & Southbridge Controllers]
        C4[BIOS Firmware Node]
        C5[Bus & Peripheral Interface]
    end

    subgraph Biological Neural Framework
        B1[Central Nervous System]
        B2[Diencephalon Array]
        B3[Cerebral Cortex Processor]
        B4[Brainstem I/O Gateway]
        B5[Peripheral Neural Network]
    end

    subgraph Analogical Relays
        A1[CPU ↔ Thalamus Map]
        A2[Northbridge ↔ Hypothalamus Link]
        A3[Southbridge ↔ Epithalamus Channel]
        A4[Memory ↔ Cortex Bridge]
        A5[Bus ↔ PNS Bus Line]
    end

    subgraph Inputs
        I1[User Input Signals]
        I2[Environmental Sensory Data]
        I3[System Boot/Power Events]
    end

    subgraph Outputs
        O1[Processed Thought Patterns]
        O2[Motor/Peripheral Commands]
        O3[Behavioral Execution Pathways]
    end

    %% Core connections
    CORE --> C1
    CORE --> B1
    CORE --> A1
    CORE --> I1
    CORE --> O1

    %% Inputs feeding system
    I1 --> C2
    I2 --> B2
    I3 --> C4

    %% Computer structure
    C1 --> C2
    C1 --> C3
    C1 --> C4
    C1 --> C5

    %% Brain structure
    B1 --> B2
    B1 --> B3
    B1 --> B4
    B1 --> B5

    %% Analogical bridges
    C2 --> A1 --> B2
    C3 --> A2 --> B2
    C3 --> A3 --> B2
    C5 --> A5 --> B5
    C4 --> A4 --> B3

    %% Outputs
    B3 --> O1
    B5 --> O2
    B4 --> O3

    %% Final feedback loop
    O1 --> CORE
    O2 --> CORE
    O3 --> CORE
