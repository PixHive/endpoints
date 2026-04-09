# endpoints

Daily WARP endpoint test results generated from the endpoint selection logic used by `yonggekkk/warp-yg`.

## Files

- `warp/ipv4.txt`: best IPv4 endpoints, one `IP:PORT` per line.
- `warp/ipv4.csv`: best IPv4 endpoints with `endpoint,loss,delay_ms`.
- `warp/ipv4.json`: same data as JSON for scripts.
- `warp/ipv4.meta.json`: generation metadata.

Consumers can read the raw file directly, for example:

```bash
curl -fsSL https://raw.githubusercontent.com/PixHive/endpoints/main/warp/ipv4.txt
```
