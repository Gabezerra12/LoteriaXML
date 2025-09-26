# 📱 LoteriaXML

Aplicativo Android desenvolvido em Kotlin no Android Studio que simula um sorteio de números da loteria e mantém um histórico de sorteios utilizando banco de dados SQLite.
Idealizado por Gabriel Bezerra Ledezma
---

## ✨ Funcionalidades
- 🎲 **Gerar Números da Loteria**  
  - Sorteia 6 números únicos entre **1 e 60**.  
  - Exibe os números formatados (ex: `05 - 12 - 23 - 41 - 55 - 60`).  

- 💾 **Salvar no Banco de Dados (SQLite)**  
  - Cada sorteio é registrado em uma tabela chamada `sorteios`.  
  - Os dados ficam persistidos no banco `loteria.db`.  

- 📜 **Listar Histórico de Sorteios**  
  - O usuário pode visualizar todos os sorteios anteriores em uma `ListView`.  
  - Os resultados são listados em ordem decrescente (do mais recente para o mais antigo).  

---

## 🛠️ Tecnologias Utilizadas
- **Kotlin** (linguagem principal)  
- **Android Studio** (IDE)  
- **SQLite** (persistência local de dados)  
- **Componentes Android**:  
  - `TextView`, `Button`, `ListView`  
  - `SQLiteDatabase`, `SQLiteStatement`  
  - `ArrayAdapter`

---

## 📂 Estrutura do Projeto
LoteriaXML/
├── app/
│ ├── manifests/ (AndroidManifest.xml)
│ ├── java/com/example/loteriaxml/ (MainActivity.kt)
│ ├── res/
│ │ ├── layout/activity_main.xml
│ │ ├── values/ (strings, colors, themes)
│ │ └── mipmap/ (ícones do app)
├── build.gradle (Project)
├── build.gradle (Module :app)
└── settings.gradle.kts

---
