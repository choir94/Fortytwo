## Fortytwo Node (CPU VPS Setup)

Many node runners assume a GPU VPS is required for @fortytwo, but in reality, a standard CPU-based setup still runs fine for testing and stability purposes.

I've been running mine on a **Digital Ocean VPS (8 GB RAM / 4 CPU)**, and it's been working smoothly.  
To make it easier for others, I’ve modified the setup script for lighter and more efficient performance on non-GPU servers.

### Installation

Run this command on your VPS terminal:

```bash
wget https://raw.githubusercontent.com/choir94/Airdropguide/refs/heads/main/42.sh -O 42.sh && chmod +x 42.sh && ./42.sh
