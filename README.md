# CoCoSySTeM_GPT

> Plataforma de inteligencia artificial, automatización y desarrollo impulsada desde Termux.

## 🚀 Acerca del Proyecto
**CoCoSySTeM_GPT** es un entorno de desarrollo e infraestructura de software optimizado para ejecutarse en entornos móviles y locales (Linux/Termux), integrando modelos de lenguaje avanzados como Qwen mediante `llama.cpp` y automatización de despliegues en GitHub.

## 🛠️ Tecnologías y Herramientas
* **Entorno:** Termux (Android)
* **Motor de IA:** `llama.cpp` (`llama-server`) con modelos GGUF (Qwen 3B)
* **Control de Versiones:** Git y GitHub (`aliascoco27`)
* **Automatización:** Scripts personalizados en Bash (`~/.bashrc`)

## ⚙️ Uso rápido del Servidor de IA
Para levantar el servidor localmente en el puerto `8080`:
```bash
cd ~/llama.cpp && ./build/bin/llama-server -m models/qwen2.5-3b-instruct-q4_k_m.gguf -c 1024 -np 1 --port 8080
