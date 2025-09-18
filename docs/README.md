<h1> <span class="rainbow-text" style="color:MediumSeaGreen; text-align:center; font-size:4rem;">Unreal Dub Engine</span></h1>

<h1> Minecraft server guide | <span class="rainbow-text"> play.unrealdub.club</span></h1>

<button id="theme-toggle">☀️ Light Mode</button>

<h3 style="text-align:center; color:Pink;">

<details>

<summary><span style="text-align:center; color:pink;">Mod list</span></summary>

<span style="font-weight:light; font-size:.75rem; color:grey;">I have not confirmed each mod is working, let me know if you notice any that are broken</span>
<br>

[Amendments](https://www.curseforge.com/minecraft/mc-mods/amendments/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Cobblemon](https://www.curseforge.com/minecraft/mc-mods/cobblemon)<br>
[Comforts](https://www.curseforge.com/minecraft/mc-mods/comforts/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Create](https://www.curseforge.com/minecraft/mc-mods/create/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Distant Horizons](https://www.curseforge.com/minecraft/mc-mods/distant-horizons/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Farmer's Delight](https://www.curseforge.com/minecraft/mc-mods/farmers-delight/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Just Enough Items](https://www.curseforge.com/minecraft/mc-mods/jei/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Lootr](https://www.curseforge.com/minecraft/mc-mods/lootr)<br>
[Supplementaries](https://www.curseforge.com/minecraft/mc-mods/supplementaries/files/all?page=1&pageSize=20&version=1.21.1)<br>
[Waystones](https://www.curseforge.com/minecraft/mc-mods/waystones)<br>
[Xaeros Mini Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap)<br>
[Xaeros World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)<br>

</details>

</h3>

## &#9733; Downloads & Setup

### <span style="color:pink">Java 21</span>

1. [Download](https://adoptium.net/download?link=https%3A%2F%2Fgithub.com%2Fadoptium%2Ftemurin21-binaries%2Freleases%2Fdownload%2Fjdk-21.0.8%252B9%2FOpenJDK21U-jdk_x64_windows_hotspot_21.0.8_9.msi&vendor=Adoptium)
2. Run & complete the downloaded `OpenJSK21U…` .msi file
3. Complete install using default options
4. (Optional) Check version: 
   - Launch Command Prompt (windows > 'cmd') 
   - Enter `java --version`
   - openjdk version should be `21.0.8` (or at least `21.x.x`)

### <span style="color:orange">CurseForge</span>

1. [Download](https://download.overwolf.com/install/Download?ExtensionId=cfiahnpaolfnlgaihhmobmnjdafknjnjdpdabpcm&utm_term=eyJkb21haW4iOiJjZi13ZWIifQ%3D%3D)
2. Run & complete the downloaded installer

### <span style="color:olivedrab">Custom modpack</span>

1. Open the #minecraft channel in the Discord server
2. Click the **Download modpack** link in the channel header
3. Open CurseForge
4. Under 'My Modpacks', select 'Import'
5. Select **Import from ZIP**
6. Select the downloaded .zip file


## &#9733; Recommended | <span style="color:MediumSeaGreen">Restore minecraft settings</span>

Installing a modpack creates a new minecraft folder, which means your settings will be reset to default*. This includes video settings, keybinds, and probably some other shi

Lets fix that:

1. Open your **existing minecraft folder**
> - Open File Explorer
> - In the navigation bar, type `%appdata%` and hit enter
> - Open .minecraft
2. Find **options.txt**, right click, **copy** (NOT cut!)
3. Open <span style="color:orange">CurseForge</span>
4. Right click the modpack under **My Modpacks**
5. Click **Open folder**
6. **Paste** the copied file into the folder, and **Replace the file** if prompted

 **Your existing minecraft installations will still have your original settings, don't worry!*

## &#9733; Recommended | <span style="color:MediumSeaGreen">Increase available RAM</span>

1. In <span style="color:orange">CurseForge</span>, click the **settings** icon in the bottom left
2. Under Game Specific on the left, click **Minecraft**
3. Scroll to the bottom and increase the **Allocated Memory**
   - I suggest at least 8GB (8192MB), but higher is better. 16GB is 16384MB

<br>

# <span style="color:Pink; font-weight: bold;">Launching the game</span>

---

1. In <span style="color:orange">CurseForge</span>, hover over the modpack and click **Play**
2. Minecraft launcher will open, the selected version should have **neoforge** in the name
3. Play! If prompted, check the *"I understand..."* box and continue
4. It will take a long time (3+ minutes) to launch, especially the first time
5. Some additional windows will likely open, just minimize those and close after playing

<h6> v1.2 </h6>


<style>
body {
  background-color: #121212; /* dark by default */
  color: #e0e0e0;
  font-family: sans-serif;
  transition: background-color 0.4s, color 0.4s;
  padding: 1rem;
}

/* Button styles */
#theme-toggle {
  position: fixed;
  top: 1rem;
  right: 1rem;
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  font-size: 1rem;
  background: #333;
  color: #fff;
  transition: background 0.3s, color 0.3s;
}

/* Light mode overrides */
body.light-mode {
  background-color: #ffffff;
  color: #121212;
}

body.light-mode #theme-toggle {
  background: #eee;
  color: #121212;
}

.rainbow-text {
  font-weight: bold;
  background: linear-gradient(
    270deg,
    #ff4b5c,
    #ffb347,
    #47d147,
    #47b8ff,
    #b347ff,
    #ff4b5c
  );
  background-size: 1200% 1200%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
          background-clip: text;
          color: transparent;

  animation: rainbowShift 12s ease infinite;
}

@keyframes rainbowShift {
  0%   { background-position: 0% 50%; }
  50%  { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

h1 {
  text-align: center;
}

h1 {
  border-bottom: none !important;
}

</style>

<script>
const btn = document.getElementById("theme-toggle");

btn.addEventListener("click", () => {
  document.body.classList.toggle("light-mode");
  btn.textContent = document.body.classList.contains("light-mode")
    ? "🌙 Dark Mode"
    : "☀️ Light Mode";
});
</script>