```markdown
# 🚀 Curso Progressivo para Programador Roblox Studio + Lua  
*Objetivo: criar jogos com scripts, interface, economia e monetização no Roblox Studio*

---

## 🗓️ Cronograma de 4 Semanas

| Semana | Habilidades principais                             | Vídeo (copiar e colar no navegador)                 |
|--------|----------------------------------------------------|-----------------------------------------------------|
| 1      | Interface do Studio, Lua básico, client vs server  | [EP 01 – Crie um JOGO COMPLETO no Roblox do ZERO](https://www.youtube.com/watch?v=5qcIo1ifKBk) :contentReference[oaicite:0]{index=0} |
| 2      | Eventos (Touched, Click, Prompt), `Instance.new`   | *mesmo canal* (continue série iniciada no EP 01) :contentReference[oaicite:1]{index=1} |
| 3      | leaderstats, DataStore simples, RemoteEvent/Function | [Guia completo de scripting, RemoteEvents e leaderboard (PT‑BR)](https://www.youtube.com/watch?v=XZ7cEUWN-YU) :contentReference[oaicite:2]{index=2} |
| 4      | Importar modelos 3D, GamePass/GameDevProduct, monetizar | [How to Import Blender Models to Roblox Studio in 2025](https://www.youtube.com/watch?v=aT7AUgU0VVc) :contentReference[oaicite:3]{index=3} |

---

## 📚 Módulos da Semana 1  
- Configurar e usar o **Roblox Studio** (Explorer, Properties, Toolbox).  
- Entender a diferença entre **Script (server)** e **LocalScript (client)**.  
- Aprender Lua: variáveis, operadores, condições, loops e funções.  
- Primeira tarefa: scriptar um botão que troca a cor de um objeto com `ClickDetector` ou `ProximityPrompt`.

---

## 🎮 Módulos da Semana 2  
- Detectar interações (`Touched`, `Activated`, `MouseClick`).  
- Criar objetos em runtime com `Instance.new` (e deletar com `:Destroy()`).  
- Usar **Parenting** e organizar objetos logicamente.  
- Projeto: botão-teleporte e porta que abre/fecha automaticamente após X segundos.

---

## 📊 Módulos da Semana 3  
- Implementar `leaderstats` para contador de moedas ou pontos.  
- Capturar eventos de coleta e atualizar UI com `ScreenGui`, `TextLabel`, `ImageButton`.  
- Comunicação segura Client ↔ Server usando `RemoteEvent` ou `RemoteFunction`.  
- Armazenamento simples de dados com DataStore (salvar e recuperar moeda).

---

## 💰 Módulos da Semana 4  
- Importar modelos `.FBX` produzidos com Blender no Studio (usar Asset Manager).  
- Criar **GamePass** ou **Developer Product** no painel da Roblox.  
- Configurar scripts para detectar compras via `MarketplaceService`.  
- Finalizar mini‑jogo com pontuação, compra de poder (GamePass), e publicar o build.  
- Criar ícone, miniatura e título personalizados para o jogo.

---

## 📁 Estrutura mínima de pastas (no seu PC)

```

/CursoProgramadorRoblox/
├── Semana1/
│   └── script\_cor\_mudanca.lua
├── Semana2/
│   └── porta\_trigger.lua
├── Semana3/
│   └── sistema\_moedas/
│       ├── coleta\_module.lua
│       ├── leaderboard\_server.lua
│       └── ui\_player.local.lua
└── Semana4/
├── imports/
│   ├── casa\_lowpoly.fbx
│   └── poste\_fachada.fbx
├── scripts/
│   ├── gamepass\_handler.lua
│   └── data\_store\_save.lua
└── projeto\_final.rbxl

```

---

## ✅ Checklist de Atividades por Semana

<details>
<summary>Semana 1 ✅</summary>
- [ ] Instalar e explorar o Studio  
- [ ] Configurar botão com `ClickDetector`  
- [ ] Menu do objeto mudar de cor ao clicar  
- [ ] Tags e nomes claros em Explorer  
</details>

<details>
<summary>Semana 2 ✅</summary>
- [ ] Porta que abre ao toque e fecha após 5s  
- [ ] Entender `Touched` vs `Click`  
- [ ] Criar obj. como items com `Instance.new`  
- [ ] Testar em modo `Play Solo` e `Start Server`  
</details>

<details>
<summary>Semana 3 ✅</summary>
- [ ] Adicionar versus coletáveis no cenário  
- [ ] Atualizar `leaderstats` ao coletar  
- [ ] Criar UI de pontuação funcional  
- [ ] Implementar `RemoteEvent` entre client‑server  
</details>

<details>
<summary>Semana 4 ✅</summary>
- [ ] Importar meshes Blender como `MeshPart`  
- [ ] Script de compra de GamePass ou DevProduct  
- [ ] Mini‑jogo completo com interatividade e monetização  
- [ ] Criar ícone, miniatura e abrir para público  
</details>

---

## 🚀 Próximos Passos  
- Criar versão Markdown deste README com links clicáveis em Notion, GitHub ou Trello.  
- Usar versionamento (Git) para controlar o progresso do projeto.  
- Compartilhar com o artista para alinhar entregas semana a semana.

**Boa jornada na criação do seu jogo no Roblox!** 💪
::contentReference[oaicite:4]{index=4}
```

