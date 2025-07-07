# 🛠️ Tecmod Arena BR – _O Legado Não Morre!_ 🛠️

**Modpack NeoForge 1.21.1 | 🎮 Tech + RPG + Arena Multiplayer**

---

## 📋 Sumário

- [Descrição](#descrição)  
- [Conteúdo](#conteúdo)  
- [Instalação](#instalação)  
- [Estrutura do Repositório](#estrutura-do-repositório)  
- [Contribuição](#contribuição)  
- [Licença](#licença)

---

## 🧭 Descrição

**Tecmod Arena BR** combina tecnologia avançada e ambientação RPG com arenas PvP/PvE, todos compatíveis com **NeoForge 1.21.1**.

---

## 🚀 Conteúdo

### 🎲 Mods de RPG/Ambientação

- **Serilum’s RPG Bundle – 1.21.1‑2.4** — bundle completo de mods de ambientação, compatível com NeoForge 1.21.1 :contentReference[oaicite:1]{index=1}  
- **Collective – 1.21.x** — biblioteca necessária para o RPG Bundle :contentReference[oaicite:2]{index=2}  

### 🔧 Mods de Tecnologia

- **PneumaticCraft: Repressurized – 8.2.12** (Minecraft 1.21.1, NeoForge) :contentReference[oaicite:3]{index=3}  
- *(Adicione aqui outras versões confiáveis dos seus mods de tecnologia, como Create, RFTools, Mekanism, Thermal, AE2 etc.)*

---

## ⚙️ Instalação

### Cliente

1. Instale o *NeoForge 1.21.1* no seu launcher.  
2. Copie `mods/`, `config/` e `scripts/` deste repositório para sua pasta `.minecraft/`.  
3. Verifique estes arquivos `.jar`:
`

4. Inicie o Minecraft com o perfil NeoForge.

### Servidor

1. Baixe o *server-pack* na aba *Releases* do GitHub (já contém mods e NeoForge).  
2. Extraia no diretório do servidor.  
3. Abra `eula.txt` e defina `eula=true`.  
4. Utilize o comando de startup (ajuste caminho conforme necessário):
   ```bash
   java -Xmx8G @user_jvm_args.txt \
     @libraries/net/neoforged/neoforge/1.21.1-<versão>/unix_args.txt nogui
