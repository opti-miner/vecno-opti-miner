# Vecno Opti Miner

Optimized GPU Miner for Vecno - CUDA accelerated.

## Performance

- **44 MH/s** on RTX 3070 Ti
- CUDA optimized with minimal memory footprint

## Download

Download the latest release from the [Releases](https://github.com/DefensioMiner/vecno-opti-miner/releases) page.

## Usage

```bash
chmod +x vecno-opti-miner
./vecno-opti-miner --mining-address vecno:YOUR_ADDRESS -s grpc://127.0.0.1:7110
```

## Requirements

- Linux x86_64
- NVIDIA GPU with CUDA support (Compute Capability 6.1+)

## Options

```
--mining-address    Your Vecno wallet address
-s, --server        Node address (default: grpc://127.0.0.1:7110)
--cuda-device       Select specific GPU device
```
