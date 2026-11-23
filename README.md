<img width="716" height="1600" alt="WhatsApp Image 2026-11-22 at 9 31 15 " src="https://github.com/user-attachments/assets/7d3b60c3-7ce7-462f-b056-a920c3a49837" />
<img width="716" height="1600" alt="WhatsApp Image 2026-11-22 at 9 31 15 PM" src="https://github.com/user-attachments/assets/5d14e1ab-4982-420d-83a5-0963c7c28848" />
 #TaskChain - Lista de Tareas en Solana

Proyecto final del curso de Solana. Aplicación descentralizada para gestionar tareas on-chain.

## Ruta elegida
Proyecto guiado - TaskChain

## Propósito
Permitir a los usuarios crear, consultar y completar tareas que quedan guardadas de forma permanente en la blockchain de Solana, sin depender de un servidor central.

## Programa Desplegado
- *Network:* Devnet
- *Program ID:* BDXBt8kucfQCnntkfNw23rHESJQvaeyHRRbMfXp7SdMk
- *Explorer:* https://explorer.solana.com/address/BDXBt8kucfQCnntkfNw23rHESJQvaeyHRRbMfXp7SdMk?cluster=devnet
- *Upgrade Authority:* 5SssZTNrQDb61g4oQ2uqNBFb2cDiWpHnQXmHFP5nc67V

## Configuración
1. Instalar Node.js, Rust y Solana CLI
2. Clonar este repositorio
3. Instalar dependencias: npm install
4. Configurar la wallet en Devnet: solana config set --url devnet

## Pasos de ejecución
1. anchor build
2. anchor deploy
3. cd app && npm run dev
4. Conectar wallet en Devnet y crear una tarea

## Funcionalidades / Aporte propio
- Crear tarea con título y descripción
- Marcar tarea como completada
- Listar tareas desde on-chain
- Interfaz conectada con la wallet del usuario

## Cómo probarlo
1. Abrir la app y conectar wallet en Devnet
2. Crear una tarea nueva
3. Verificar la transacción en el Explorer
4. Marcar la tarea como completada y verificar el cambio on-chain

## Pruebas y Evidencias
- Deploy exitoso en Devnet: Deployment successful
- Program ID verificado en Explorer: Executable: Yes
