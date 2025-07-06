# 🛠️ Tecmod Arena BR – *O Legado Não Morre!* 🛠️

**Modpack NeoForge 1.21.1 | 🎮 Tech + RPG + Arena Multiplayer**

---

## 📋 Sumário

- [Descrição](#descrição)  
- [Conteúdo](#conteúdo)  
- [Instalação](#instalação)  
  - Cliente  
  - Servidor  
- [Estrutura do Repositório](#estrutura-do-repositório)  
- [Contribuição](#contribuição)  
- [Licença](#licença)

---

## 🧭 Descrição

**Tecmod Arena BR** é um modpack criado para servidores e aventuras solo, mesclando tecnologia avançada e ambientação RPG/arena:

- 🔧 **Tech**: Create, PneumaticCraft, RFTools, Mekanism, Thermal, AE2  
- 🏰 **RPG/Arena**: Serilum’s RPG Bundle, Curios, dungeons YUNG’s, Towns and Towers  
- 🛠️ Integração com sistema de quests, combate, arenas PvP/PvE e automação steampunk

---

## 🚀 Conteúdo

- **Mods Principais**  
  - *Create*, *PneumaticCraft: Repressurized*, *RFTools* (Utility/Power/Dimensions)  
  - *Mekanism*, *Thermal Series*, *Applied Energistics 2*  
  - *Serilum’s RPG Bundle*, *Curios API*, *YUNG's Better Worlds*, *Towns and Towers*

- **Scripts e Configs**  
  - Configurações customizadas para balanceamento (energia, loot, spawn)  
  - Questbook (FTB Quests) com progressão Tech e Arena

- **Servidor**  
  - Scripts para instalação e startup com NeoForge  
  - `.jar` correto e `unix_args.txt` para Java 17+

---

## ⚙️ Instalação

### Cliente

1. Instale o *NeoForge 1.21.1* (via launcher Prism/Cursed).
2. Copie `mods/`, `config/` e `scripts/` deste repositório para `.minecraft/`.
3. Inicie o Minecraft com perfil NeoForge.
4. Faça login no servidor ou jogue single-player.

### Servidor

1. Baixe o *server-pack* da release (inclui mods e NeoForge server-jars).
2. Extraia no diretório do servidor.
3. Confirme que `eula.txt` esteja como `eula=true`.
4. Execute o script:
   ```bash
   java -Xmx8G @user_jvm_args.txt @libraries/net/neoforged/neoforge/1.21.1-…/unix_args.txt nogui
