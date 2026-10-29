# Squeek Odometer

How far has Squeektoshi run? A tiny fan-made dashboard for the hamster-powered [Squeekchain](https://x.com/squeekchain).

- Live wheel status: running / resting, speed, rpm, tonight's distance
- Lifetime distance, block height, work units, settlements on Sepolia
- Nightly distance chart (last 30 days)
- "Hamster units": marathons, track laps, Eiffel Towers
- Guess tonight's km (saved locally in your browser)

Live: https://syk808.github.io/squeek-odometer/

Single static `index.html`, no build step, no backend. Data comes from the public Squeekchain API (`api.squeekchain.com/v1`) on Sepolia testnet and refreshes every 10 seconds.

Not affiliated with the Squeekchain team. Built by [@syk233](https://x.com/syk233).

MIT License
