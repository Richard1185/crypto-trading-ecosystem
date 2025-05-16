# Ecosistema de Trading Cripto

Un sistema avanzado de trading automatizado para criptomonedas que incluye análisis técnico, machine learning y gestión de riesgos.

## Características Principales

- Bot de trading multi-activo
- Análisis técnico avanzado (MACD, RSI, Bollinger Bands, VWMA, EMA)
- Sistema de entrenamiento y validación de estrategias
- Gestión de riesgos automatizada
- Backtesting de estrategias
- Integración con múltiples exchanges

## Requisitos

- Node.js >= 14.x
- npm >= 6.x
- MongoDB
- Redis (opcional)

## Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/[tu-usuario]/crypto-trading-ecosystem.git
cd crypto-trading-ecosystem
```

2. Instalar dependencias:
```bash
npm install
```

3. Configurar variables de entorno:
```bash
cp .env.example .env
# Editar .env con tus configuraciones
```

## Uso

Para iniciar el bot de trading:
```bash
npm start
```

Para ejecutar el backtesting:
```bash
npm run backtest
```

## Estructura del Proyecto

```
crypto-trading-ecosystem/
├── src/
│   ├── bots/           # Bots de trading
│   ├── indicators/     # Indicadores técnicos
│   ├── strategies/     # Estrategias de trading
│   ├── utils/          # Utilidades
│   └── api/            # API endpoints
├── tests/              # Tests unitarios
├── config/             # Configuraciones
└── docs/              # Documentación
```

## Contribuir

1. Fork el proyecto
2. Crear una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abrir un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Tu Nombre - [@tutwitter](https://twitter.com/tutwitter)

Link del Proyecto: [https://github.com/[tu-usuario]/crypto-trading-ecosystem](https://github.com/[tu-usuario]/crypto-trading-ecosystem) 