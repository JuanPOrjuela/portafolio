# Hechos verificados para el portafolio (no inventar nada fuera de esto)

Persona: Juan Pablo Orjuela Rojas. Estudiante de 5.º semestre de Ciencias de la
Computación e Inteligencia Artificial, Universidad Sergio Arboleda, Bogotá,
Colombia (UTC-5). GitHub: github.com/JuanPOrjuela. Busca trabajo remoto
part-time en evaluación de IA / datos / QA. Español nativo, inglés para
lectura técnica. NO poner correo, teléfono ni LinkedIn (se agregan luego).

## 1. EvalCO — banco de evaluación de LLMs en español colombiano (2026)
- 150 casos escritos a mano en 5 categorías de 30: seguimiento de
  instrucciones, razonamiento (pesos COP, IVA 19 %, fechas), colombianismos
  (opción múltiple), atención al cliente con política de empresa, y
  alucinaciones (premisas falsas, con 6 controles de premisa verdadera).
- 115 casos con verificadores deterministas (16 tipos: números con formato
  colombiano, regex, JSON, conteo de palabras/viñetas, etc.), 35 con juez LLM y
  rúbrica sí/no. Intervalos de Wilson 95 %. Solo biblioteca estándar de Python.
- Modelos evaluados localmente con Ollama en una RTX 3070 Ti de 8 GB:
  qwen3:8b, deepseek-r1:8b, hermes3:8b. RESULTADOS: dejar marcadores
  {{EVALCO_TABLA}} y {{EVALCO_HALLAZGOS}} que se llenarán después.
- Repo: aún no publicado → enlace marcador {{EVALCO_URL}}.

## 2. evangelionPL — lenguaje de dominio específico para ciencia de datos (2026)
- Proyecto del curso Lenguajes de Programación (grupo de 3: Julian Beltrán,
  Juan Pablo Orjuela, Santiago Ortegón). Gramática ANTLR4 + intérprete en Python.
- Regla del curso: sin librerías hechas (sin pandas, NumPy ni Matplotlib).
  Tablas propias, lista enlazada propia, regresión, perceptrón con 4
  activaciones, red neuronal y árboles propios; gráficas (barras, líneas,
  histograma, dispersión, caja) dibujadas a mano en PNG/SVG, con un codificador
  PNG propio (DEFLATE, CRC-32, Adler-32) y una fuente de 5x7 hecha a mano.
- Palabras clave en español, más de 160 pruebas, manual en PDF.
- Repo público: https://github.com/JuanPOrjuela/evangelionPL

## 3. Momentum paper — estrategia de inversión simulada y auditable (2026)
- Simulación (paper trading, sin dinero real) multiactivo: cripto (BTC, ETH,
  SOL…), acciones y ETF (QQQ, SPY, AAPL, MSFT, NVDA, TSLA) y diversificadores
  (GLD, TLT, DBC). Regla de momentum por ensamble de ventanas 20/50/100/200
  días; QQQ a 1,5x; comisiones incluidas.
- Corre sola cada día con GitHub Actions y guarda el estado en el repo.
- Backtest 2021-2026: CAGR +23,2 %, Sharpe 1,39, caída máxima −27,7 %, contra
  comprar y mantener lo mismo: +26,7 %, Sharpe 1,01, caída −48,9 %. Es decir:
  rinde algo menos, pero con mucho menos riesgo. DECIRLO ASÍ, sin exagerar.
- En vivo desde el 27-oct-2026: al 10-nov −4,5 % contra −9,2 % de comprar y
  mantener (el mercado cayó; la regla perdió la mitad).
- Auditoría: cuadre contable (efectivo + posiciones = patrimonio), sin
  look-ahead, manejo de splits y dividendos.
- Repo PRIVADO: no poner enlace.

## 4. Sitio y agenda para un spa de mascotas en Bogotá (2026, cliente)
- Es de un cliente (el negocio y los ingresos son del dueño). Next.js
  desplegado en Cloudflare Workers (OpenNext), base de datos Turso (libSQL),
  pagos con Wompi, catálogo, agenda de servicios, panel, reseñas, SEO técnico
  (Search Console, sitemap, datos estructurados JSON-LD).
- Agente de WhatsApp con menú (en desarrollo). Más de 400 pruebas automáticas.
- Sitio: https://kiragopets.com (se puede enlazar). Repo PRIVADO.

## 5. Sistemas operativos e IA local (2026)
- Instalación completa de Gentoo Linux con KDE Plasma (Wayland) en VM e informe
  técnico APA (grupo de 4).
- Taller de IA local con Ollama en máquinas virtuales:
  https://github.com/JuanPOrjuela/tallerOllama1 (grupo).
- Servidor con IA local para un cliente simulado (taller de clase).
