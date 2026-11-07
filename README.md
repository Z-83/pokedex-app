# Pokédex App

App en React + Vite que consume PokéAPI con Axios. Incluye estados de carga y error, filtrado local por nombre y despliegue continuo en Vercel/Netlify.

## Uso local
```bash
npm install
npm run dev
```
Crea un archivo `.env` (ver `.env.example`) con `VITE_POKEAPI_URL=https://pokeapi.co/api/v2`.

## Producción
```bash
npm run build
```
Configura `VITE_POKEAPI_URL` en las Environment Variables de Vercel o Netlify.
