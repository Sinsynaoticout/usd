# Synaptic Sovereign Pay (Terminal USD T+0)

Terminal independiente de cobro y liquidación transfronteriza para tarjetas de crédito chilenas (cupo en dólares internacional) hacia liquidez inmediata.

## URL de Producción
- Consola de Emisión: https://sinsynaoticout.github.io/usd/cobro-usd.html
- Terminal Exclusivo para Cliente: https://sinsynaoticout.github.io/usd/cobro-usd.html?u=5000&method=card

## Arquitectura
- **Frontend:** Single-screen reactive cockpit (HTML5 + Zero-CDN Vanilla CSS + Vanilla JS).
- **Procesador Bancario 3D-Secure:** Enrutamiento directo a operador internacional sin fricción KYC.
- **Bóveda de Liquidación:** Polygon POS (`0xf730319057663fc62bc6dfc75bd3857e380dc520`).
- **Acreditación:** Instantánea en Binance Spot (USDC/USDT).
