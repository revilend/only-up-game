
## Faqat Tepaga! — 3D Parkur (2000m)

Brauzer va mobil telefonlar uchun yaratilgan **3D vertikal parkur** o'yini. Yashil o'tloq lobbisidan boshlab Shahar, Bulutlar, Stratosfera, **1000m Oltin Lobbi** hamda **1000m–2000m Kosmos** (Oy Orbitasi, Mars & Asteroidlar, Galaktika Cho'qqisi) orqali eng yuqoriga ko'tariling.

Hech qanday server yoki API kalitisiz, bitta `index.html` faylida to'liq ishlaydi.

## Asosiy imkoniyatlar

- **2000 metrlik ikki bosqichli dunyo:**
  - **0m – 1000m (Yer va Osmon):** O'tloq Lobbi, Shahar (yuk mashinalari), Bulutlar va Stratosfera (havodagi 3D samolyotlar), yakunda **1000m Oltin Lobbi** (tashqi zina, 3D Do'kon va Kosmosga start batuti).
  - **1000m – 2000m (Kosmos):** Oy Orbitasi, Mars & Asteroidlar, Saturn va yulduzli osmon, **Qora Tuynuklar** (tortishish kuchi va Slingshot bonusi), **Kvant Portallar** (yuqoriga teleport) hamda **2000m Galaktika Cho'qqisi** lobbisi.
- **3D Do'kon va Moneta tizimi:** Barcha 3 ta lobbida (0m, 1000m, 2000m) 3D Do'kon maydonchasi hamda istalgan balandlikdan ochiladigan yuqori **Moneta + DO'KON** tugmasi. Qahramonlar, Jetpack, Slow-Mo hamda doimiy kuchaytirishlar (Sakrash kuchi, Yugurish tezligi, Yulduz ko'paytirgich) mavjud.
- **50 metrli benzinli 3D Jetpack:** Tugmani bosib ushlab turing — personaj orqasida ikkita raketali 3D Jetpack paydo bo'lib, 50 metrgacha uchish imkonini beradi (qolgan benzin saqlanib qoladi).
- **Interaktiv mexanikalar va topshiriqlar:** Havo halqalari (+25% tezlik va +20% sakrash), yashirin 3D sandiqlar, golografik ko'prik tugmalari, sinuvchi oynalar, aylanuvchi lazerlar va jonli topshiriqlar (`TOPSHIRIQ`).
- **Qo'shimcha rejimlar va sozlamalar:** Tungi Neon rejim, 200m Speedrun poygasi, balandlikka qarab yomg'ir/qor effekti, **Ko'rish burchagi (FOV)** (50°–100°), **Ekran surish tezligi** (0.4x–2.5x) va gorizontal/portret ekran boshqaruvi.
- **Mobilga moslashgan boshqaruv:** Chap hududda barmoq qo'yilgan joyda paydo bo'ladigan suzuvchi joystik, o'ng tomonda kechikishsiz multi-touch **SAKRA**, **Jetpack** va **Slow-Mo** tugmalari.
- **Bosqichga mos fon musiqasi:** O'tloq, Osmon/Stratosfera va Kosmos zonalari uchun studiya MP3 treklari.

## Boshqaruv

| Harakat | Telefon (Mobil) | Kompyuter (Klaviatura / Sichqoncha) |
| --- | --- | --- |
| Yurish / Yugurish | Chap tarafdagi suzuvchi joystik | `W A S D` + `Shift` |
| Sakrash / 2x Sakrash | `SAKRA` tugmasi | `Space` |
| Jetpack (bosib uchish) | `Jetpack` tugmasini bosib turish | `F` (bosib turish) |
| Vaqtni sekinlashtirish | `Slow-Mo` tugmasi | `T` |
| Kamerani burish | O'ng ekranni surish | Sichqoncha bilan surish / `Q E` |
| Qayta boshlash | Yuqori o'ngdagi qayta yuklash tugmasi | `R` |

## Ishga tushirish (GitHub Pages)

1. O'yin faylini repozitoriy ildiziga `index.html` nomi bilan yuklang.
2. GitHub repozitoriyda **Settings → Pages** bo'limini oching.
3. **Branch** sifatida `main` va `/ (root)` ni tanlab **Save** bosing.
4. Bir necha daqiqadan so'ng o'yin `https://<username>.github.io/<repo-nomi>/` manzilida ishga tushadi.

## Texnologiyalar va manbalar

- **3D Dvigatel:** [Three.js](https://threejs.org/) (`r128`) va `GLTFLoader`
- **3D Modellar (glTF / GLB):**
  - Qahramonlar va qushlar: [Three.js Examples](https://github.com/mrdoob/three.js) (`Soldier.glb`, `RobotExpressive.glb`, `Xbot.glb`, `Parrot.glb`, `Flower.glb`)
  - Shahar va kosmik obyektlar: [KhronosGroup glTF-Sample-Assets](https://github.com/KhronosGroup/glTF-Sample-Assets) (`CesiumMilkTruck.glb`, `Duck.glb`, `DamagedHelmet.glb`)
  - NASA Astronavti: [Google Model-Viewer](https://github.com/google/model-viewer/blob/master/packages/shared-assets/models/Astronaut.glb) (`Astronaut.glb`)
  - Yashirin sandiq va kristallar: [Webaverse Assets](https://github.com/webaverse/assets) (`chest.glb`, `crystal.glb`)
  - 3D Samolyotlar: [utkuhalis/ps3-homebrew](https://github.com/utkuhalis/ps3-homebrew) (`jet.glb`) va [Vibe_coding_pj_1](https://github.com/Harshit-Khetan-31/Vibe_coding_pj_1) (`plane.glb`)
- **Musiqa (CC BY 4.0):** Kevin MacLeod ([Incompetech](https://incompetech.com/agent-section/)) — *Carefree*, *Neon Laser Horizon*, *Ossuary 6 - Air*, *Heart of Nowhere*.
