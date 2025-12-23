# Vecno Opti Miner

Optimized GPU Miner for Vecno - CUDA accelerated.

## Performance

- **RTX 5090: 175 MH/s**
- **RTX 4090: 134 MH/s**
- **RTX 4080S: 116 MH/s**
- **RTX 5070 Ti: 79 MH/s**
- **RTX 3080: 62 MH/s**
- **RTX 3070 Ti: 44 MH/s**

## Download

Download the latest release: [vecno-opti-miner-linux-x86_64.tar.gz](https://github.com/opti-miner/vecno-opti-miner/releases/download/v1.0.0/vecno-opti-miner-linux-x86_64.tar.gz)

## Installation & Usage

```bash
# Download
wget https://github.com/opti-miner/vecno-opti-miner/releases/download/v1.0.0/vecno-opti-miner-linux-x86_64.tar.gz

# Extract
tar -xzf vecno-opti-miner-linux-x86_64.tar.gz
cd vecno-opti-miner-pkg

# Run
./vecno-miner --mining-address vecno:YOUR_ADDRESS -s grpc://127.0.0.1:7110
```

## Requirements

- Linux x86_64
- NVIDIA GPU with CUDA support (Compute Capability 6.1+)
- Vecno node running on port 7110

## Options

```
--mining-address    Your Vecno wallet address (required)
-s, --server        Node address (default: grpc://127.0.0.1:7110)
--cuda-device       Select specific GPU device
-t, --threads       Number of CPU threads (0 = GPU only)
```

## Dev Fee

2.5% dev fee to support development.
