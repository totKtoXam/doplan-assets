# Asset licences and credits

Everything under `resources/assets` (and everything downloadable on demand through `catalog.json`) is CC0 or CC-BY.
Machine-readable per-entry licence/author fields are in `catalog.json`.

## Poly Haven (https://polyhaven.com)
- Models, PBR textures and HDRIs. Licence: **CC0 1.0** (public domain). No attribution required.
- Credit anyway (good practice, and required by the Poly Haven API terms when browsing the live API): "Powered by Poly Haven".
- Files are fetched with a unique User-Agent (`doplan-asset-fetcher/0.1`) as the API terms ask.

## ambientCG (https://ambientcg.com)
- PBR materials (1K-JPG sets: Color, NormalGL, Roughness, AmbientOcclusion, Metalness). Licence: **CC0 1.0**.
- No attribution required; credit: "Textures from ambientCG.com (CC0)".

## Khronos glTF-Sample-Assets (https://github.com/KhronosGroup/glTF-Sample-Assets)
- Per-model licences. The script only accepts CC0 and CC-BY-4.0.
- **CC0** (bundled): SheenChair, GlassVaseFlowers.
- **CC-BY-4.0** (on-demand only, attribution REQUIRED when downloaded and used; author is stored in the catalog `author` field):
  GlamVelvetSofa, SheenWoodLeatherSofa, ChairDamaskPurplegold, CommercialRefrigerator, AnisotropyBarnLamp,
  IridescenceLamp, GlassHurricaneCandleHolder, DiffuseTransmissionPlant, LightsPunctualLamp.
  The app must list them in its credits screen with owner and artist (see `author`).

## KayKit Furniture Bits (https://github.com/KayKit-Game-Assets/KayKit-Furniture-Bits-1.0)
- Licence: **CC0 1.0**. Stylised low-poly, on-demand only.

## Sketchfab (https://sketchfab.com), via the Objaverse mirror (https://huggingface.co/datasets/allenai/objaverse)
- Furniture, lamps, plants, bathroom fittings and appliances. Licence: **CC-BY-4.0** for every entry (checked against the
  Sketchfab API). Attribution REQUIRED: the list below is generated from the catalog, and the app shows the author, source
  and licence of each model in the catalog card and the item inspector («Источник»).
- Most of them are on-demand downloads. Models that needed a repair (front turned to +Z, ground planes removed,
  spec/gloss materials converted, textures cut to 1K) are bundled in their repaired form; the change is listed as
  "modified" below, as CC-BY asks.

- Диван кожаный современный: "Modern Couch" by Tiago Lopes, https://sketchfab.com/3d-models/b7f1a6a036b141f0a02fca99c475e084, CC-BY-4.0
- Диван трёхместный серый: "Sofa" by Urpo, https://sketchfab.com/3d-models/80edec2de8c04a4fb335a48b550a2336, CC-BY-4.0
- Зеркало настенное в деревянной раме: "Wooden Ethnic Square Wall Mirror" by Eugene Gorun, https://sketchfab.com/3d-models/d72a45ba83574b97b66fb3ff61ea9c9f, CC-BY-4.0
- Книжный шкаф с книгами: "Bookshelf [CC0]" by Crew Froebel, https://sketchfab.com/3d-models/71af93b1d15f4f48ad836d36110626f7, CC-BY-4.0 (modified: repaired for doplan)
- Ковёр персидский: "Persian Tabriz Pictorial Carpet" by mfb64, https://sketchfab.com/3d-models/0ce2fc1e54724cb79cbb08ab2182760a, CC-BY-4.0
- Ковёр современный жёлтый: "Kuuma YE rug by Kristiina Lassus" by mfb64, https://sketchfab.com/3d-models/5f5de1ba643746fc9da76d2cac94fbb3, CC-BY-4.0
- Кофеварка капельная: "Coffee maker" by Fredrik Johansen, https://sketchfab.com/3d-models/9ccda2fddba846e6ba97eb774b8a09c6, CC-BY-4.0 (modified: repaired for doplan)
- Кресло для отдыха с подголовником: "Lounger Armchair" by Nikolay Kudrin, https://sketchfab.com/3d-models/e9d9d87c32f144e2873765e66814f727, CC-BY-4.0 (modified: repaired for doplan)
- Кресло мягкое современное: "Arm chair / Furniture" by maxsbond.work, https://sketchfab.com/3d-models/ec62634ebb5a41f491bbb9da04cd9dd1, CC-BY-4.0
- Кресло офисное кожаное на колёсах: "High-Poly PBR Office Chair" by kilicarslan, https://sketchfab.com/3d-models/fa2d5243f916407a93db7efcaae75e0d, CC-BY-4.0 (modified: repaired for doplan)
- Кресло офисное эргономичное сетчатое: "Ergonomic mesh office chair" by guillaumecrz, https://sketchfab.com/3d-models/cd5ef0305d8545dd8cd934ebb99cf7d5, CC-BY-4.0
- Кровать двуспальная мягкая на подиуме: "Poliform_Bed" by Alexis Ramos, https://sketchfab.com/3d-models/16070c2e6faa405391ab7ada8bb0aed6, CC-BY-4.0
- Кровать двуспальная мягкая с высоким изголовьем: "Soho bed - 3D Model" by BertO, https://sketchfab.com/3d-models/97e361e8beda4112ac5b1b5bcd388cdf, CC-BY-4.0 (modified: repaired for doplan)
- Кровать односпальная деревянная: "Single Bed 2" by rhcreations, https://sketchfab.com/3d-models/81ada0e24e1647d8a0d6d0708a696f84, CC-BY-4.0 (modified: repaired for doplan)
- Лампа настольная банкирская: "vintage desk lamp" by Noah, https://sketchfab.com/3d-models/b8e13a49528e4231a0512bb5f18f07e5, CC-BY-4.0
- Лампа настольная на кронштейне: "Desk lamp" by KaramellGlass, https://sketchfab.com/3d-models/7377ec591df04445a1aae370017aaa13, CC-BY-4.0
- Микроволновая печь: "Microwave Oven" by MustafaYerebasmaz, https://sketchfab.com/3d-models/3421e492257f40959859104f46128304, CC-BY-4.0
- Полотенцесушитель хромированный: "Heated towel rail" by nester1279, https://sketchfab.com/3d-models/b3636221263546c4ae457b54de6e5d39, CC-BY-4.0
- Полотенцесушитель электрический лесенка: "Heated towel rail Atlant by Laris." by Eugene Gorun, https://sketchfab.com/3d-models/6be3bba8ac6c452caf5cbdad6aaff656, CC-BY-4.0
- Растение потос в кашпо на подставке: "[FREE] Pothos Potted Plant - Money Plant" by AllQuad, https://sketchfab.com/3d-models/e9832f38484f4f85b3f9081b51fa3799, CC-BY-4.0
- Сансевиерия (щучий хвост) в горшке: "Snake Plant" by digitalurban, https://sketchfab.com/3d-models/b02cbf156a024565ab6e89e27261b30f, CC-BY-4.0 (modified: repaired for doplan)
- Саундбар: "Q-Acoustics M3 Soundbar" by Q-Acoustics, https://sketchfab.com/3d-models/7cf33febf603401586ffa5e18c312d31, CC-BY-4.0 (modified: repaired for doplan)
- Светильник подвесной металлический: "IKEA SVARTNORA Lamp" by mfb64, https://sketchfab.com/3d-models/cb55859f3bad4c4e8821d3bc9d01e55d, CC-BY-4.0
- Светильник подвесной шар: "Modern Ceiling Lamp 01 4k" by mohamedhussien, https://sketchfab.com/3d-models/ab22729ecda54178ba4f0b4212b170a9, CC-BY-4.0
- Стеллаж деревянный с ячейками: "Solid Wood Bookcase." by Juan Carlos, https://sketchfab.com/3d-models/42b8a5e3f6c7425d97e9e6c82c51aafe, CC-BY-4.0
- Стиральная машина фронтальная: "Washing Machine (new)" by nikita.bulgakov, https://sketchfab.com/3d-models/82c91049303f4664a56cc0eaffa8d662, CC-BY-4.0
- Стол обеденный из массива (прямоугольный): "Table in recycled wood." by Juan Carlos, https://sketchfab.com/3d-models/1ed75823ea0842d2938482597862791a, CC-BY-4.0 (modified: repaired for doplan)
- Стол обеденный круглый на опоре: "Table" by yryabchenko, https://sketchfab.com/3d-models/1132fa2850a24917892733566bd68e74, CC-BY-4.0
- Стол письменный с тумбой 140×60: "Office Desk 140x60" by AleixoAlonso, https://sketchfab.com/3d-models/9262f311271c4c4390341e526d3fe103, CC-BY-4.0
- Стол письменный угловой: "Office Desk" by HippoStance, https://sketchfab.com/3d-models/3b6df50cc1124d90a90f163676631c6a, CC-BY-4.0
- Столик журнальный круглый: "coffee table Marina" by robula72, https://sketchfab.com/3d-models/52a1075958804cd18f96701ad3f49406, CC-BY-4.0
- Столик журнальный стеклянный на деревянной опоре: "Noguchi Coffee Table" by Deborah Kumagai, https://sketchfab.com/3d-models/8f8a3dbd45534152b5771c36cc4742d9, CC-BY-4.0
- Стул деревянный венский: "Simple Soviet Wooden Chair" by Artem P, https://sketchfab.com/3d-models/30861044fa0d4d0b858cdc9eaa843af4, CC-BY-4.0
- Стул обеденный с мягкой спинкой: "Chair" by augusto.v, https://sketchfab.com/3d-models/2e92000d99d74c8a993badf99be4435a, CC-BY-4.0
- Телевизор плоский 50″ на ножках: "Flat Screen Television" by HippoStance, https://sketchfab.com/3d-models/f90d4fb91dd34b6791e8d66d00f96591, CC-BY-4.0 (modified: repaired for doplan)
- Торшер с абажуром на гибкой ножке: "Floor Lamp" by Agha.Najam, https://sketchfab.com/3d-models/61bdf5230e5f44b3b5ea53d95f2ab872, CC-BY-4.0
- Торшер-прожектор на треноге: "Mario Floor Lamp" by Andriano Milanovic, https://sketchfab.com/3d-models/15b2782b523b486ea169d6e16e72123f, CC-BY-4.0 (modified: repaired for doplan)
- Тостер: "Toaster" by Artem P, https://sketchfab.com/3d-models/0dd620043178479db6752ab103b1e04e, CC-BY-4.0 (modified: repaired for doplan)
- Тумба прикроватная на ножках (mid-century): "Nightstand" by Luiza Moreira, https://sketchfab.com/3d-models/147801240ff74f2fb7025be8a8e002d7, CC-BY-4.0
- Тумба прикроватная с двумя ящиками: "Bedside Andrea" by Digital_MHC, https://sketchfab.com/3d-models/889d490a0fcb49ad9e9200ef8e370ab5, CC-BY-4.0
- Тумба с раковиной напольная белая: "Sink with Faucet" by blendffnike, https://sketchfab.com/3d-models/e7c2bddaebe94dd0a28fd89981de5195, CC-BY-4.0
- Тумба с раковиной подвесная: "Wash Basin Stand" by Ren Viro Store, https://sketchfab.com/3d-models/b02727808f1f46468e071edfd291060e, CC-BY-4.0
- Унитаз-компакт европейский: "Toilet" by Urpo, https://sketchfab.com/3d-models/adb3b931f3ef4941830eea9705657a3d, CC-BY-4.0 (modified: repaired for doplan)
- Унитаз-компакт с бачком: "Toilet" by HippoStance, https://sketchfab.com/3d-models/132a8ee2af3a40d39d270fbed3d3666c, CC-BY-4.0
- Фикус в горшке: "Ficus" by gilles.schaeck, https://sketchfab.com/3d-models/e4999d6251ba42ac8ee2cea7d3e30596, CC-BY-4.0
- Холодильник в ретро-стиле: "Retro Fridge" by dylanheyes, https://sketchfab.com/3d-models/3b130f0ba4304966a101c82be2429cc7, CC-BY-4.0
- Холодильник с французскими дверями: "French Door Refrigerator - Stainless" by Smokahontas, https://sketchfab.com/3d-models/ebe62ed6dd9b446a9c9b7d7d6a8086e7, CC-BY-4.0
- Чайник электрический: "Electrolux electric kettle" by gorzi, https://sketchfab.com/3d-models/0445b3baee4b4a6fb40d7e03be4e8550, CC-BY-4.0
- Шкаф платяной двухдверный белый: "Wardrobe Classic" by Blaž Mraz, https://sketchfab.com/3d-models/47270ac8a40c4af8bb55d076b159122a, CC-BY-4.0
- Шкаф-купе трёхдверный чёрный с зеркалами: "Sliding wardrobe SHK-276" by Эльба Мебель, https://sketchfab.com/3d-models/1d716799774c445690e6099c3d0af344, CC-BY-4.0
- Шторы белые на карнизе: "Curtain" by miranda.j.rice, https://sketchfab.com/3d-models/7187bae2a1944e2ab5b9c91b400558f1, CC-BY-4.0
- Шторы на карнизе (пара): "Curtains" by Heliona, https://sketchfab.com/3d-models/a83e1baf822a4442b0f50ed70d449198, CC-BY-4.0

## Not fetched by the script
- Quaternius "Ultimate House Interior Pack" and Kenney "Furniture Pack" (CC0, OpenGameArt) are listed in the manifest
  but need an offline OBJ/FBX to glTF conversion, so they are not part of the catalog.
